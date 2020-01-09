pipeline {
  agent {
    docker {
      image 'guest_docker'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('') {
      steps {
        withGradle()
      }
    }

  }
}