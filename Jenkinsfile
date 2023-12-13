pipeline {
  agent any
  options {
    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
  }
  stages {
    stage('Hello') {
      steps {
        git url: 'https://github.com/awsfree0001/jenkins_pub.git'
        bat '''
        dir
        '''
      }
    }
  }
}