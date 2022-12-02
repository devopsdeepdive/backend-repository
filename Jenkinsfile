pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/blueocean-repo.git', branch: 'master', credentialsId: 'github_cred	')
      }
    }

  }
}