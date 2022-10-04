pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        echo 'Start of pipeline'
        echo 'Second Step in branch 3'
      }
    }

    stage('error') {
      steps {
        sleep 2
        echo 'Sleep for 2 seconds'
      }
    }

    stage('Build') {
      steps {
        echo 'In build in build'
      }
    }

  }
}
