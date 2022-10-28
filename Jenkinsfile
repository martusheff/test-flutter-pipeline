pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/martusheff/test-flutter-pipeline', branch: 'master')
      }
    }

    stage('Test') {
      steps {
        sh 'flutter test'
      }
    }

  }
}