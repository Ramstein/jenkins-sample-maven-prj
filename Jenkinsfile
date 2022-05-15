pipeline {
  agent any

  stages {
    stage('maven install') {
      steps {
        withMaven( maven: 'Maven3.8.5') {
            sh 'mvn clean install'
        }
      }
    }
  }
}