pipeline {
  agent any
  tools {
    maven 'maven-3.6.3' 
  }
  stages {
    stage ('Build') {
      steps {
        bat 'mvn clean package'
      }
    }
    stage ('Deploy') {
      steps {
       echo 'Deployed'
      }
    }
  }
}
