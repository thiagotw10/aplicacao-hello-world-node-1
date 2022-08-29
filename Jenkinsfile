pipeline {
  agent any

  tools { nodejs 'Node LTS' }

  stages {
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }

    stage('Test') {
      steps {
        sh 'npm test'
      }
    }
  }
}
