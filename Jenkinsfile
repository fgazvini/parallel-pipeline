pipeline {
  agent none
  stages {
    stage('foo') {
      parallel {
        stage('first') {
          steps {
            sh 'echo "first branch"'
          }
        }
        stage('second') {
          steps {
            sh 'echo "Second branch"'
          }
        }
      }
    }
  }
}