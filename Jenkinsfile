pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
  environment {
    node = '-p 3000:3000'
  }
}