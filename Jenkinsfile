pipeline {
   agent any
   stages {
      stage('Build'){
        steps{
          sh "docker build -t jmalonsollamas/pokedex-flask:${env.BUILD_NUMBER} ."
        }
      } 
   }
}
