pipeline {
  agent any
  stages {
    stage('NPM') {
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }

  }
}