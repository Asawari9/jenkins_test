pipeline {
  agent none
  stages {
    stage('asa2') {
      parallel {
        stage('asa2') {
          steps {
            echo 'done with1'
          }
        }
        stage('asa1') {
          steps {
            echo 'asawari d'
          }
        }
      }
    }
  }
}