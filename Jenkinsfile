pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('Validation') {
      steps {
        sh '''pip install pytest
python pytest'''
      }
    }

  }
}