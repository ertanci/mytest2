pipeline {
  agent any
  stages {
    stage('version check') {
      parallel {
        stage('version check') {
          steps {
            echo 'selam'
            sh 'ansible --version'
          }
        }

        stage('error') {
          steps {
            echo 'merhaba'
          }
        }

        stage('nana') {
          steps {
            retry(count: 2) {
              echo 'tata'
            }

          }
        }

      }
    }

    stage('write tata') {
      steps {
        echo 'tata'
      }
    }

  }
}