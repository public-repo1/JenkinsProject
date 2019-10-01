note{
    stage('SCM Checkout'){
        git 'https://github.com/ParkHyeokJin/JenkinsProject'
    }
    stage('Complile-Package'){
        def mvnHome = tool name: 'm3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}
