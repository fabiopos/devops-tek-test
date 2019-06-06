pipeline {
  agent any
  stages {
    stage('npm install') {
      steps {
        sh 'npm install'
      }
    }
    stage('run unit test') {
      steps {
        sh 'npm run test'
      }
    }
    stage('start') {
      steps {
        sh 'npm start'
      }
    }
  }
}