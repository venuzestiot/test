pipeline {
  agent any
  stages {
    stage('initilization') {
      parallel {
        stage('initilization') {
          steps {
            echo 'echo "hello world"'
            build(job: 'avileap', propagate: true, quietPeriod: 3, wait: true)
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