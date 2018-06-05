pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${MY_NAME}!!!!1"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Emmanuel'
  }
}