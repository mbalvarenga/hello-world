node{
  stage('SCM Checkout'){
    git 'https://github.com/mbalvarenga/repository-test'
  }
  stage('Compile-Package'){
    // Get maven home path
    def mvnHome = tool name: 'maven-360', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
  
}  
