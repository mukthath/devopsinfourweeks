pipeline {
  agent any
  stages {
    stage('buzz build') {
      parallel {
        stage('buzz build') {
          steps {
            echo 'buzz1'
          }
        }

        stage('buzzsetup') {
          steps {
            echo 'buzz2'
          }
        }

      }
    }

    stage('test') {
      steps {
        sleep 6
      }
    }

  }
}