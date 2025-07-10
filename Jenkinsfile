pipeline {
  agent {
    node {
      label 'jkagent'
    }
    docker {
      image 'php:8.4.8-alpine3.22'
    }
  }
  stages {
    stage('construire') {
      steps {
        sh 'php --version'
      }
    }
  }
}
