pipeline{
  agents any
  stages{
    stage('Git checkout'){
      steps{
        script{
          git branch: 'main', url: 'https://github.com/yaseen-yusha/java-app.git'
        }
      }
    }
   } 
}
