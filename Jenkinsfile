node {
  
  stage('SCM Checkout'){
     
    	url: 'https://github.com/shameem2019/jenkinsdemo'   
   }

  stage('Compile-Package'){
       def mvnHome=tool name: 'maven-3', type: 'maven'
       sh "${mvnHome}/bin/mvn package"
       }
   }
