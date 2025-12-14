pipeline {
  agent any
  stages {
    stage('Git-Clone') {
      steps {
        git(poll: true, url: 'https://github.com/BilalMaz/CloudApp.git', branch: 'main')
      }
    }

  }
}