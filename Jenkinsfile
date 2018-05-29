pipeline {
  agent any
  stages {
    stage('\'Say Hello\'') {
      steps {
        echo 'Hello World! '
      }
    }
    stage('testing123') {
      environment {
        MY_NAME = 'Mary'
      }
      steps {
        sh 'java -version'
        echo 'testing4567'
      }
    }
  }
}