pipeline {
  agent any
  stages {
    stage('prova'){
      steps{
        sh 'echo ciao'
      }
    }
    stage('run'){
      steps {
        sh '/bin/bash script.sh'
      }
    }
    stage('result'){
      steps{
        sh 'ls -l'
      }
    }
  }
}
