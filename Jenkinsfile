pipeline {
  agent any
  stages {
    stage('Dev') {
      parallel {
        stage('Dev') {
          steps {
            echo 'development sstage'
          }
        }

        stage('Testing') {
          steps {
            echo 'testing stage'
          }
        }

        stage('Plugin ') {
          steps {
            echo 'plugin stage'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'QA Stage'
      }
    }

    stage('UAT') {
      steps {
        echo 'UAT stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'deploy stage'
      }
    }

    stage('Operate') {
      steps {
        echo 'operate stage'
      }
    }

  }
}