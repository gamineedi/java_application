pipeline{
  agent any
  
  environment{
    M2_HOME = "/var/lib/jenkins/apache-maven-3.9.6"
  }
  stages{
    stage("checkout"){
      steps{
        checkout scm
      }
    }
    
    stage("unit Test"){
      steps{
        sh '${M2_HOME}/bin/mvn clean test:test'
      }
    }
  }
}
