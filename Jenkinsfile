#!groovy

pipeline {
  agent none
  stages {
    stage('Tomcat Install') {
      agent {
        docker {
          image 'tomcat'
        }
      }
    } 
  }
}
