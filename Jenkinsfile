pipeline {
  agent any
  stages {
    stage('stage1') {
      agent any
      steps {
        sh '''uname -a
whoami
id'''
        sh 'pwd'
      }
    }

    stage('stage2') {
      agent any
      steps {
        sh '''pwd
ls -al'''
      }
    }

  }
}