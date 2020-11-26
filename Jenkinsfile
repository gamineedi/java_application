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
        sh 'mvn clean test:test'
      }
    }
  }
}
