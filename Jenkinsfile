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
        bat 'C:\apache-maven-3.6.1\bin\mvn clean package'
      }
    }
  }
}
