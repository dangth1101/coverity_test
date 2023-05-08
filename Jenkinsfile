pipeline {
  agent { label 'linux' }
  stages {
    stage('check') {
      steps {
        checkout scm
      }
    }
    stage('compile') {
      steps {
         sh 'python3 python_test.py'
      }
    }
  }
}
