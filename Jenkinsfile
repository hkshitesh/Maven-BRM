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
    stage ('Deploy') {
      steps {
       echo 'Deployed'
      }
    }
  }
}
