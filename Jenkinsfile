pipeline {
  agent  { label 'agent_python' }
  stages {
    stage('test code') {
      steps {
        sh 'ls'
      }
    }
    stage('Python Version Check') {
      steps {
        sh "python appy.py"
      }
    }

  }
}
