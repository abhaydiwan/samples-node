 pipeline {
  agent { label 'Jen-Slave' } {
    docker { image 'node:latest' }
  }
  
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
