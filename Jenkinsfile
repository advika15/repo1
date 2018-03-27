pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'echo "This is compile"'
      }
    }
    stage('UITest') {
      steps {
        sh 'echo "UITest"'
      }
    }
    stage('Deploy') {
      steps {
        bat 'echo "Deploy"'
      }
    }
  }
}