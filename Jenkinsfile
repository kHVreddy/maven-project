pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/kHVreddy/maven-project.git', branch: 'master', credentialsId: 'git_credentials')
      }
    }

    stage('BUILD') {
      steps {
        sh '''/usr/share/maven/bin/mvn clean package
'''
      }
    }

  }
}