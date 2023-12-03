pipeline {
  agent any
  stages {
    stage('check') {
      steps {
        git(url: 'https://github.com/rhoumajeder/test-tmp-repo.git', branch: 'master')
      }
    }

    stage('install') {
      steps {
        sh '''yarn install
'''
      }
    }

  }
}