pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            bat 'echo "Ashish"'
            bat 'echo "Hello World"'
          }
        }

        stage('ParallelTest') {
          steps {
            echo 'This is parallel step'
          }
        }

      }
    }

    stage('Stage2') {
      steps {
        powershell 'get-service'
      }
    }

    stage('Stage3') {
      steps {
        timestamps() {
          echo 'Current time'
        }

      }
    }

  }
}