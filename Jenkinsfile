pipeline {
  environment {
      MY_NAME = 'Mary'
   }
  agent {
    label 'jdk9'
  }
  stages {
    stage('say hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
  }
}
