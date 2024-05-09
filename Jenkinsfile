pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Hello my name is shubh'
        sh '''pwd
date'''
      }
    }

    stage('Try') {
      steps {
        sleep 10
      }
    }

    stage('Time') {
      steps {
        timestamps() {
          echo 'Time check'
        }

      }
    }

    stage('Bye') {
      steps {
        fileExists 'Dockerfile'
      }
    }

  }
}