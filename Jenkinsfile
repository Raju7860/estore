pipeline{
  agent any 
  stages{
    stage('Source'){
      steps{
         git branch:'main',url:'https://github.com/Raju7860/estore-Admin.git'
      } 
    }

    stage('Compile'){
      steps{
        bat "npm install"
    }
      } 
    
      stage('Test'){
      steps{
        bat "npm run test "
    }
      } 
    
     stage('Build'){
      steps{
        bat "npm run build"
    }
      } 
    
  }
}