pipeline
{
agent any
  environment
  stages{
    stage('GetCode'){
      steps{
        git branch: 'master'
        url: 
      }
    }
    stage('Build'){
      steps{
       sh 'mvn clean package' 
      }
    }
  }   
}
  
