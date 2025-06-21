pipeline {
  agent any
  stages {
    stage('Maven Version') {
      steps {
        sh 'echo Print Maven Version'
      }
    }

    stage('Build') {
      steps {
        sh 'echo test building'
       
      }
    }

    stage('Test') {
      steps {
        sh 'echo tested'
      }
    }
    
    stage('Local Deployment') {
      steps {
        sh """ echo done """
      }
    }
    
    


  }
  

}
