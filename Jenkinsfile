
pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      echo 'running build now'
      sh './gradlew build --no-daemon'
      }
    }  
  }
}
