pipeline {
  agent any
  stages {
    stage('initilization') {
      parallel {
        stage('initilization') {
          steps {
            echo 'echo "hello world"'
          }
        }

        stage('test') {
          steps {
            echo 'echo "testing done"'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'echo "deployment is done'
      }
    }

  }
}