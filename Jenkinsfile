pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'hello-world'
          }
        }

        stage('Parallel') {
          steps {
            echo 'top of the morning'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'hiiiii'
      }
    }

    stage('Clean up') {
      steps {
        echo 'heyooo'
      }
    }

  }
}