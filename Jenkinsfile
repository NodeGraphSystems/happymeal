pipeline {
  agent {
    node {
      label 'docker-jenkins'
    }

  }
  stages {
    stage('checkout from git') {
      steps {
        git(url: 'https://github.com/NodeGraphSystems/happymeal.git', branch: 'master', credentialsId: 'afdeacebd91b6c401b6ab1f610ad8a835cfdaee0')
      }
    }
  }
}