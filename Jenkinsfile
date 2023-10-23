pipeline {
   agent any
   stages {
      stage('Build'){
        steps{
          sh "docker build -t jmalonsollamas/prueba3:${env.BUILD_NUMBER} ."
        }
      } 
   }
}
