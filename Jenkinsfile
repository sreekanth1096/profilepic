pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        echo 'Hello World'
        sh 'echo "hello from shell script"'
      }
    }

    stage('second hello') {
      steps {
        echo 'Hello again'
      }
    }

  }
}