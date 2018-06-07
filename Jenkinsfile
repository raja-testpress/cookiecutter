pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh 'docker-compose -f local.yml build'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}