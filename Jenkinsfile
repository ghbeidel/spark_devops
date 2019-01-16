pipeline {
  agent any
  stages {
    stage('First Stage') {
      steps {
        echo 'Hello World'
      }
    }
    stage('Mvn') {
      steps {
        sh 'mvn clean package -DskipTests'
      }
    }
  }
}