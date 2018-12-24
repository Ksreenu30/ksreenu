pipeline {
  agent none
  stages {
    stage('Initialize') {
      steps {
        echo 'This is to just print a message.'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn -Dmavn.test.failure.ignore= install'
      }
    }
  }
}