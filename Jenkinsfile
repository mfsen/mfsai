pipeline {
  agent any
  stages {
    stage('updateCode') {
      steps {
        git(url: 'https://github.com/mfsen/mfsai.git', branch: 'dev')
      }
    }

    stage('updateDir') {
      steps {
        sh 'ls -la'
      }
    }

  }
}