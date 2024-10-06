pipeline {
  agent {
    label 'agent_python'
  }
  stages {
    stage('test code') {
      steps {
        sh 'ls'
      }
    }

    stage('update') {
      steps {
        sh 'yum update -y'
      }
    }

  }
}