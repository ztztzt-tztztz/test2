pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh 'ls'
        sh 'echo "this is a test"'
      }
    }

    stage('List Files') {
      steps {
        sh 'ls -l'
      }
    }

    stage('Echo Message') {
      steps {
        sh 'echo "Hello, Jenkins!"'
      }
    }

  }
}