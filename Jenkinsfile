@Library('my-shared-library') _

pipeline{
  
  agent any
  
  stages{
  
    stage('Git checkout'){
    
      steps{
      gitCheckout{
            branch:"main"
            url: 'https://github.com/yaseen-yusha/java-app.git'
      }
     }
    }
  } 
}
