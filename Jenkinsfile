pipeline {
  agent any
  stages {
    stage('demostage2') {
      steps {
        sh './jenkins/build.sh'
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
      }
    }

  }
}