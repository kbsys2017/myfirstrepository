pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Test'
        sh '''echo "QA"
'''
      }
    }

    stage('QA') {
      steps {
        sh 'echo "QA"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "Deploy"'
      }
    }

  }
}