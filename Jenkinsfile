pipeline {
  agent {
    node {
      label 'docker-slave'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }
    stage('Testing') {
      steps {
        echo 'Testing...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying...'  
      }
    }
}
