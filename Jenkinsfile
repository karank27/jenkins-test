pipeline {
  agent any
  stages {
    stage('node version check') {
      steps {
        sh 'node -v'
      }
    }

    stage('npm version check') {
      steps {
        sh 'npm -v'
      }
    }

    stage('install dependency') {
      steps {
        sh 'npm install'
      }
    }

    stage('build') {
      steps {
        sh 'npm run ng build'
      }
    }

  }
}