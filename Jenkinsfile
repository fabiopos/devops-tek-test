pipeline {
  agent any
 
  tools {nodejs "node"}
 
  stages {
    stage('Cloning Git') {
      steps {
        git 'https://github.com/fabiopos/devops-tek-test.git'
      }
    }
      
    stage('Example') {
      steps {
        sh 'npm install'
      }
    }
    
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