pipeline {
  agent any
  stages {
    stage('Unit test') {
      parallel {
        stage('Unit test') {
          steps {
            sh 'ls'
          }
        }
        stage('function') {
          steps {
            sh 'ps '
          }
        }
      }
    }
  }
}