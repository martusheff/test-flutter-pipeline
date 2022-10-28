pipeline {
  agent any
  stages {
    stage('Checkout Repo') {
      steps {
        git(url: 'https://github.com/martusheff/test-flutter-pipeline', branch: 'master')
      }
    }

  }
}