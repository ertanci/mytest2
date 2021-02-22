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
      parallel {
        stage('write tata') {
          steps {
            echo 'tata'
          }
        }

        stage('ozan') {
          steps {
            build 'job2'
            powershell(script: 'ertan.ps1', returnStatus: true, returnStdout: true)
          }
        }

      }
    }

  }
}