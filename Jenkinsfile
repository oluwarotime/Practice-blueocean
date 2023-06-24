pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        git(url: 'https://github.com/oluwarotime/Practice-blueocean.git', branch: 'main')
      }
    }

    stage('stage2') {
      steps {
        echo 'Hello World'
      }
    }

    stage('stage3') {
      steps {
        sleep 90
      }
    }

  }
}