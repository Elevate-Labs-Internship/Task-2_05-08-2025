pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'This is Build stage'
      }
    }

    stages('Test') {
      steps {
        echo 'This is Test stage'
      }
    }

    stage('Release') {
      steps {
        echo 'This is deploy stage'
      }
    }
  }
