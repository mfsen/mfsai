pipeline {
  agent any
  stages {
    stage('updateCode') {
      steps {
        git(url: 'https://github.com/mfsen/mfsai.git', branch: 'main')
      }
    }

    stage('updateDir') {
      steps {
        sh 'cp -r /var/jenkins_home/workspace/mfsai_main/* /var/personalWeb'
      }
    }

  }
}