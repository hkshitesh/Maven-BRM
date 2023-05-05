pipeline {
  agent any
  tools {
    maven 'MAVEN_HOME' 
  }
  stages {
    stage ('Clean') {
      steps {
       bat 'mvn clean'
      }
    }
    stage ('Test') {
      steps {
        bat 'mvn test'
      }
    }    
    stage ('package') {
      steps {
        bat 'mvn package'
      }
    }   
    stage ('Deploy') {
      steps {
       echo 'Deployed'
      }
    }
  }
}
