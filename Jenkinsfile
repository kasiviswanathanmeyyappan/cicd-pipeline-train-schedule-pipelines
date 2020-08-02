pipeline {
agnet any
 stages{
 
  stage('Build'){
   steps {
   
    echo 'Running build automation'
    sh '.gradlew build --no-dademon'
    archiveArtifcats artifacts: 'dist/trainSchedule.zip'
   }  
  }   
 } 
}
