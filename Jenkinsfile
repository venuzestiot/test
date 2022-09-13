pipeline {
  agent any
  stages {
    stage('init') {
      parallel {
        stage('init') {
          steps {
            echo 'echo "hello world"'
          }
        }

        stage('test') {
          steps {
            echo 'echo "test"'
          }
        }

        stage('deploy') {
          steps {
            echo 'echo "deploy'
          }
        }

      }
    }

    stage('end') {
      steps {
        echo 'echo "end"'
      }
    }

  }
}