pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/ehmedowais/CICD.git', branch: 'master', changelog: true, poll: true)
      }
    }
  }
}