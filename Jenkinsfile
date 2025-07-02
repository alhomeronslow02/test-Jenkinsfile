pipeline{
  agent any
  stages{
    stage('Checkout code'){
      steps{
        git branch: 'main', 
        url: 'https://github.com/alhomeronslow02/test-Jenkinsfile'
      }
    }
    stage('Build'){
      steps{
        sh 'echo "Build image - sh cmd"'
      }
    }
    stage('Test'){
      steps{
        sh 'echo "Test app - sh cmd"'
      }
    } 
    stage('Deploy'){
      steps{
        sh 'echo "Deploy app - sh cmd"'
      }
    } 
  }
}
post{
success{
  bat 'echo "build successful"'
}
failure{
  bat 'echo "build failed"'
}
}
