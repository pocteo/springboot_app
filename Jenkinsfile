pipeline {
  agent any
    
  tools {maven "Maven_home"}
  
    
  stages {
  
    stage('clean the packages') {
      steps {
        sh 'mvn clean'
      }
    }
   stage('install the packages') {
      steps {
        sh 'mvn package'
      }
    }
    stage('run the packages') {
      steps {
        sh 'java -jar target/spring-boot-rest-example-0.5.0.jar'
      }
    } 
  }
}
