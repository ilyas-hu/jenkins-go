pipeline {
  agent {
    docker {
      image 'golang'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'XDG_CACHE_HOME=/tmp/.cache go test ./..'
      }
    }

  }
}
