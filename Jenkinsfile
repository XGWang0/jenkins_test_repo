pipeline {
  agent any
  stages {
    stage('pull_source') {
      steps {
        sh '''git pull origin master
'''
      }
    }
    stage('code_check') {
      steps {
        sh './test.sh'
      }
    }
  }
}