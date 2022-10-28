node{
  stage('SCM Checkout'){
    
    git 'https://github.com/navneet9122/webapp'
  }

stage('Compile-Package'){
   def mvnHome= tool name: 'maven2', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
      }
   }   
