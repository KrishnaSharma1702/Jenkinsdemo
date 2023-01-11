pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'pwd'
          }
        }

        stage('Hello') {
          steps {
            echo 'ITBD is the BEST'
          }
        }

      }
    }

    stage('Test') {
      steps {
        sleep 2
      }
    }

  }
}