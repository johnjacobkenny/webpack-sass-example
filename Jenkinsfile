pipeline {
  agent any
  stages {
    stage('npm install') {
      steps {
        sh 'npm install'
      }
    }
    stage('Output') {
      steps {
        sh 'npm test'
      }
    }
  }
}