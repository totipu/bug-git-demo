pipeline {
  agent {
    docker {
      image 'python'
      args '--user 0:0'
    }

  }
  stages {
    stage('Validation') {
      steps {
        sh '''pip install pytest
pytest'''
      }
    }

  }
}