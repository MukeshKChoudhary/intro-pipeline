pipeline {
  agent {
    label 'control'
  }
  stages {
    stage('Say Hello control') {
      steps {
        echo 'Hello from $MY_NAME using ENV'
        sh 'java -version'
      }
    }

  }
  environment {
    MY_NAME = 'MUKESH'
  }
}