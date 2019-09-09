pipeline{
 agent any
 stages {
   stage ('Build') {
     steps {
      echo 'Running build automation'
      sh './gradlew buold --no-deamon
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     } 
   }
  } 
}
