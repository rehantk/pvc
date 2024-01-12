pipeline {
  agent any
  stages {
    stage('one') {
      steps {
        lock('stage1') {
          echo 'stage one'
          sh 'sleep 1m'
        }
      }
    }
  }
}
