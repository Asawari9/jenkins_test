pipeline {
  agent none
  stages {
    stage('asa') {
      parallel {
        stage('asa') {
          steps {
            sh ' echo "asawari Awati"'
          }
        }
        stage('asa2') {
          steps {
            echo 'done with1'
          }
        }
      }
    }
  }
}