pipeline{
  agent any
  stages{
    stage("checkout"){
      steps{
        checkout scm
      }
    }
    
    stage("unit Test"){
      steps{
        mvn clean install
      }
    }
  }
}
