pipeline {
  agent any

  tools {
    maven 'maven3'
    jdk 'temurin8'
  }

  stages {
    stage('run') {
      steps {
        sh 'mvn verify'
      }
    }
  }
}