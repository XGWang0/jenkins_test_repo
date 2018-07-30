pipeline {
  agent any
  stages {
    stage('pull_source') {
      steps {
        sh '''git pull original jenkins_test_repo

'''
      }
    }
    stage('code_check') {
      steps {
        sh 'check code'
      }
    }
  }
}