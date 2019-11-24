pipeline{
  agent any
  stages {
  stage ('Build'){
      steps {
        echo 'Running Build authomation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifiacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
