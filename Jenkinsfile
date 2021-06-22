pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('stpe1') {
          steps {
            echo 'step 1'
          }
        }

        stage('step2') {
          steps {
            echo 'test'
          }
        }

      }
    }

    stage('step3') {
      steps {
        echo 'step3'
      }
    }

  }
}