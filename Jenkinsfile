pipeline {
  agent any
  stages {
    stage('check'){
      steps {
        sh 'ls -l'
      }
    }
    stage('build'){
      steps {
        sh 'docker build -t image-github .'
        sh 'docker images'
      }
    }
    stage('run'){
      steps {
        sh 'docker run -d --name cont-prova image-github'
      }
    }
  }
}
