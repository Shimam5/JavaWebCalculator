pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            build 'test'
          }
        }

        stage('') {
          steps {
            sh 'clean package'
          }
        }

      }
    }

  }
}