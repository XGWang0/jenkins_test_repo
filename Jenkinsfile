pipeline {
  agent any
  stages {
    stage('pull_source') {
      steps {
        sh '''git pull original master

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