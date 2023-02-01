pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/walidanbar/Book_Git_practice', branch: 'master')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}