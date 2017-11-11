pipeline {
  agent none
  stages {
    stage('') {
      parallel {
        stage('first branch') {
          steps {
            sh 'echo "First branch"'
          }
        }
        stage('second branch') {
          steps {
            sh 'echo " second branch"'
          }
        }
      }
    }
  }
}