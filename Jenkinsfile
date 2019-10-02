pipeline {
  agent any
  stages {
    stage('SCM Checkout') {
      steps {
        git 'https://github.com/ParkHyeokJin/JenkinsProject'
      }
    }
    stage('Compile') {
      steps {
        bat "mvn -v"
      }
    }
  }
}
