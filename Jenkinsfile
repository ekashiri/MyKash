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
        MY_NAME = 'Kashiri1'
        TEST_USER = credentials('Kashiri')
      }
      steps {
        echo 'testing4567'
        echo 'testing again'
      }
    }
  }
}