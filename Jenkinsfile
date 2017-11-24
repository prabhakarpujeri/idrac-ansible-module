pipeline {
  agent any
  stages {
    stage('Unit test') {
      parallel {
        stage('Unit test') {
          steps {
            sh 'ls'
            sh 'ps aux'
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