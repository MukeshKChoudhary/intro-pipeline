pipeline {
  agent {
    label 'control'
  }
  environment {
    MY_NAME = 'MUKESH'
  }
  stages {
    stage('Say Hello control') {
      steps {
        echo 'Hello from $MY_NAME using ENV'
        sh 'java -version'
      }
    }

  }
}
