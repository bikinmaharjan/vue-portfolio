pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/bikinmaharjan/vue-portfolio', branch: 'master')
      }
    }

    stage('List Files') {
      steps {
        sh 'ls -la'
      }
    }

  }
}