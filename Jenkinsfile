pipeline {
   agent any
   stages {
     stage {'Build'} {
      steps {
         echi 'running build automation'
         sh './gradlew build --no-daemon'
         archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
      } 
    }
  } 
