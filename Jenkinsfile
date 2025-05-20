pipeline {
  agent {
    docker {
      image 'node:16.20.2-slim'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}