pipeline {
  agent {
    docker {
      image 'bitwiseman/training'
      args '-u root -v /home/jenkins'
    }

  }
  stages {
    stage('DockerImage') {
      steps {
        echo 'docker file added'
      }
    }

  }
}