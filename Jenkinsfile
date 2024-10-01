pipeline {
  agent  { label 'test' }
  stages {
    stage('test code') {
      steps {
        sh 'ls'
      }
    }
    stage('Python Version Check') {
      steps {
        sh "python3 --version"
      }
    }

  }
}
