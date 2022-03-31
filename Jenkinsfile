pipeline {
    
    agent any
    trigger 
    
  
  stages {
    
    stage("UAT") {
      
      steps {
        echo 'Build the application..'
      }
    }
    
    stage("STAG") {
      
      steps {
        echo 'Testing the application..'
      }
    }
    
    stage("PROD") {
      
      steps {
        echo 'deploying  the application..'
      }
    }
  }   
}  
