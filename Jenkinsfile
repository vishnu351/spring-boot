pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh ''' chmod +x gradlew 
               ./gradlew clean build
           '''
      }
      stage('run') {
      steps {
        sh ''' chmod +x gradlew 
               ./gradlew bootRun
           '''
      }
    }
  }
}
