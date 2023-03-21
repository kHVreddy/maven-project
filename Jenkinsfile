pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/kHVreddy/maven-project.git', branch: 'master', credentialsId: 'git_credentials')
      }
    }

  }
}