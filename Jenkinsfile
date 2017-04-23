pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo "Hello from test"'
      }
    }
    stage('build') {
      steps {
        sh 'echo "Hello from Build"'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo "Hello from Deploy phase"'
      }
    }
  }
}