pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact"
               """
           }
       }
      stage('Deploy Code to Dev') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
