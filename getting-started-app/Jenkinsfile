pipeline {
    agent any
    stages {
        stage('build'){
          steps {
            sh 'docker build -t getting-started .'
          }
        }
        stage('run'){
          steps{
            sh 'docker run -dp 3000:3000 getting-started'
          }
        }
    }
}