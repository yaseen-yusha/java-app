pipeline{
  
  agent any
  
  stages{
  
    stage('Git checkout'){
    
      steps{
      
        script{
        
          gitCheckout{
            branch:"main"
            url: 'https://github.com/yaseen-yusha/java-app.git'
        }
      }
    }
   } 
}
