pipeline {
 agent any
 stages { 
  stage('log version info') {
   step {
    sh 'mvn --version'
    sh 'mvn clean install'
   }
  }
 }
}
