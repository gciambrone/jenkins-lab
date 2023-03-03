pipeline {
  agent any
  stages {
    stage('prova'){
      steps{
        sh 'echo ciao'
      }
    }
    stage('build'){
      steps {
        sh 'docker build -t image-github .'
        sh 'docker images'
      }
    }
    stage('run'){
      steps{
        sh 'docker run -d --name cont-prova image-github'
      }
    }
  }
}
