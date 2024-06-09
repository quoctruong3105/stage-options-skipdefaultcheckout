pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        label 'Slave 1'
      }
      options {
        skipDefaultCheckout()
      }
      steps {
        echo 'Hello'
      }
    }
  }
}
