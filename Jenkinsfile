pipeline {
  agent {
    docker {
      image 'test'
    }

  }
  stages {
    stage('test') {
      steps {
        build 'hi'
      }
    }
    stage('how are you') {
      steps {
        sleep 6
      }
    }
  }
}