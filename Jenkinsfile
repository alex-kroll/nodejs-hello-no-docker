pipeline {
  agent any

  tools {nodejs "node"}
  
  environment {
        CI = 'true' 
  }

  stages {
    stage('version-info') {
      steps {
        sh 'npm --version'
      }
    }
  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
  }
}
