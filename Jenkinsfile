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
        def mvnHome = tool 'M3'
        bat "${mvnHome}\\bin\\mvn package"
      }
    }
  }
}
