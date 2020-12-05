pipeline {
  agent {
    label 'control'
  }
  stages {
    stage('Say Hello control') {
      steps {
        echo 'Hello from ${MY_NAME} using ENV'
        sh 'java -version'
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }

  }
  environment {
    MY_NAME = 'MukeshKC'
    TEST_USER = credentials('test-user')
  }
}