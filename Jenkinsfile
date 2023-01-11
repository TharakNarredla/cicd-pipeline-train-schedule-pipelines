pipeline {
  agent any 
  stages {
    stage ('Build stage') {
      steps {
        echo "running this build using automation"
        sh './gradlew build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
       }
      }
     }
        
  
