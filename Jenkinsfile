pipeline {
  agent {
    node {
      label 'any'
    }

  }
  stages {
    stage('check') {
      steps {
        git(url: 'https://github.com/rhoumajeder/test-tmp-repo.git', branch: 'master')
      }
    }

  }
}