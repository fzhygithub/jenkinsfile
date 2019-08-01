pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building1'
        echo 'Building2'
        echo 'Building3'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing1'
        echo 'Testing2'
        echo 'Testing3'
      }
    }
    stage('Deploy-Staging') {
      steps {
        echo 'Deploy-Staging1'
        echo 'Deploy-Staging2'
        echo 'Deploy-Staging3'
      }
    }
    stage('Deploy-Production') {
      steps {
        echo 'Deploy-Production1'
        echo 'Deploy-Production2'
        echo 'Deploy-Production3'
      }
    }
  }
}
