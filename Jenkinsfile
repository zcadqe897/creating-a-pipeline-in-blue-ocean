pipeline {
  agent any
  stages {
    stage('input') {
      steps {
        input(message: 'Click', ok: '0')
      }
    }
    stage('end') {
      steps {
        sleep 1
      }
    }
  }
}