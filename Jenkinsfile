pipeline {
  agent any
    
  tools {maven "Maven_home"}
    
  stages {
  
    stage('clean the packages') {
      steps {
        sh 'mvn clean package'
      }
    }
    
  }
}
