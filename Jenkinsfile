node{
    stage('SCM Checkout'){
     git 'https://github.com/praveenfun2/JenkinsTest'
    }
    stage('Complie Package'){
     def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}
