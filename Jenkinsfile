pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
        sh 'Jenkins/build.sh'
      }
    }

    stage('Testing') {
      steps {
        echo 'Testing'
        sh 'jenkins/Test.sh'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
        sh 'jenkins/deploy.sh'
      }
    }

  }
}