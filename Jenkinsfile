pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'echo "HELLO WORLD"'
        sh '''
          echo "This will list current dir content from latest"
          echo "This is a change"
          ls -lh
          '''
      }
    }
    stage ('Test') {
      steps {
        sh 'echo "Hello TEST"'
        sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
