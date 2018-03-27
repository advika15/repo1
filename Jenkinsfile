pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        bat 'echo "Deploy"'
      }
    }
    stage('UITest') {
      parallel {
        stage('UITest') {
          steps {
            bat 'echo  "UITest"'
          }
        }
        stage('Unit Testing') {
          steps {
            bat 'echo "1" '
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        bat 'echo "Deploy"'
      }
    }
  }
}