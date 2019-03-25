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
    stage('unit test') {
      steps {
        sh 'mvn test'
      }
    } 
  }
}
