pipeline{
  agent any
  stages {
    stage('prova web'){
      steps{
        sh 'echo ciao'
      }
    }
    stage('ls'){
      steps{
        sh 'ls -l'
      }
    }
    stage('run'){
      steps{
        sh '/bin/bash script.sh'
      }
    }
    stage('ls post'){
      steps{
        sh 'ls -l'
      }
    }
  }
}
