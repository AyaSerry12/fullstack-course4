pipeline {
  agent {
    node {
      label 'Test'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat(script: 'Test', returnStatus: true)
      }
    }
  }
}