pipeline {
  agent {
    node {
      label 'docker-slave'
    }

  }
  stages {
    stage('') {
      steps {
        warnError(message: 'Something goes wrong') {
          sh 'echo "It\'s working"'
        }

      }
    }

  }
}