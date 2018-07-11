pipeline {
   agent any {
  stages {
    setps ('Build) {
     steps {
      echo  'Running build automation'
      sh './gradlew build --no-daemon'
      aechiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
     }
    }
   }
  
      
