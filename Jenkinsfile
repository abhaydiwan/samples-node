 pipeline {
  agent {
    docker { 
    label 'Jen-Slave'  // both label and image
     image 'node:latest' 
    }
  }
  
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
