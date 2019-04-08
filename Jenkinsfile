node{
  stage('SCM Checkout'){
    git 'https://github.com/mbalvarenga/repository-test'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
  
}  
