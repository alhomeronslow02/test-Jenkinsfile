pipeline {
  agent any
  stages {
    stage('Checkout code') {
      git 'https://github.com/alhomeronslow02/test-Jenkinsfile'
    }
    stage('Build') {
      sh 'echo "Build image - sh cmd"'
    }
    stage('Test') {
      sh 'echo "Test app - sh cmd"'
    } 
    stage('Deploy') {
      sh 'echo "Deploy app - sh cmd"'
    } 
  }
}
