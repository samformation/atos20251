pipeline {
  agent {
    node {
      label 'jkagent'
    }
  }
  stages {
    stage('construire') {
      steps {
        sh 'docker version'
      }
    }
  }
}
