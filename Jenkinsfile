pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        bat 'echo "Ashish"'
        bat 'echo "Hello World"'
      }
    }

    stage('Stage2') {
      steps {
        powershell 'get-service'
      }
    }

  }
}