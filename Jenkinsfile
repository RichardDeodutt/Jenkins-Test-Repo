pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'echo "HELLO Tyrone"'
        sh '''
          echo "Welcome to B2"
          uname -a
          '''
      }
    }
    stage ('Test') {
      steps {
        sh 'echo "Hello Sanderson"'
        sh '''
        echo "This is testing"
        pwd
        '''
      }
    }
  }
}
