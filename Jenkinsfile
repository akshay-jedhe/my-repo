pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "hello blue ocean"'
          }
        }

        stage('build1') {
          steps {
            sh 'echo "hi"'
          }
        }

      }
    }

  }
}