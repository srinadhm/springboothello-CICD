pipeline{
    agent any 
    tools {
    maven 'maven-3.8.4'
    }
    stages {
       stage('git checkout stage'){
           steps{
               git 'https://github.com/srinadhm/springboothello-CICD.git'
           }
       }
       stage('build  stage'){
           steps{
               sh  'mvn clean package'
           }
       }
    }
    
}
