pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''ls -la 

'''
      }
    }
    stage('Tests') {
      steps {
        sleep 5
      }
    }
    stage('Aproval') {
      steps {
        input 'Voc� aprova para deploy?'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Fazendo deploy"'
      }
    }
  }
}