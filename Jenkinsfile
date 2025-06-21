
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo bulding'
      }
    }

    stage('Test') {
      steps {
        sh 'echo tesing'
      }
    }
    
    stage('Containerization') {
      steps {
        sh 'echo Docker Build Image..'
        sh 'echo Docker Tag Image....'
        sh 'echo Docker Push Image......'
      }
    }

    stage('Kubernetes Deployment') {
      steps {
        sh 'echo Deploy to Kubernetes using ArgoCD'
      }
    }
    
    stage('Integration Testing') {
      steps {
        sh "sleep 10s"
        sh 'echo Testing using cURL commands......'
      }
    }
  }
}
