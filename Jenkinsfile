node{
  stage('SCM Checkout'){
    
    git 'https://github.com/navneet9122/webapp'
  }

stage('Compile-Package'){
   def mvnHome= tool name: 'maven2', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
      }
  stage('Email Notification'){
  emailext body: 'hi welcome', subject: 'jenkin job', to: 'nkjnavneetjha317@gmail.com'
  }
   }   
