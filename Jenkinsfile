pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage 1.1') {
          steps {
            sh 'echo "Running Stage 1"'
          }
        }
        stage('Stage 1.2.1') {
          steps {
            sh 'echo "Running Stage 1.2.1"'
          }
        }
        stage('Stage 1.3') {
          steps {
            sh 'echo "Running Stage 1.3"'
          }
        }
      }
    }
  }
}