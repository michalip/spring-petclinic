pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Hello there'
        bat 'C:\\apache-maven-3.2.5\\bin\\mvn test'
      }
    }
    stage('Install') {
      steps {
        sh 'C:\\apache-maven-3.2.5\\bin\\mvn install'
      }
    }
  }
}