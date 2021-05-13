pipeline {
    
    agent any
    
    stages {
        stage ('Compile Stage') {
        
          steps{
              withmaven (maven: 'maven-3.6.3') {
                  sh 'mvn clean compile'
              }
          }
        }
        stage ('Testing Stage') {
          steps{
              withmaven (maven: 'maven-3.6.3') {
                  sh 'mvn test'
              } 
          }
        }
        stage ('Deployment Stage') {
          steps{
              withmaven (maven: 'maven-3.6.3') {
                  sh 'mvn deploy'
              } 
          }
        }
    }



}
