pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Hello i\'m here'
          }
        }
        stage('') {
          steps {
            bat 'C:/apache-maven-3.5.2/bin/mvn test'
          }
        }
      }
    }
  }
}