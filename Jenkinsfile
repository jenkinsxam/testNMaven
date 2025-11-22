pipeline {
  agent any
  stages {
    stage('demostage') {
      steps {
        echo 'helloooooo'
      }
    }

    stage('demostage2') {
      steps {
        sh './jenkins/build.sh'
      }
    }

    stage('demostage3') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}