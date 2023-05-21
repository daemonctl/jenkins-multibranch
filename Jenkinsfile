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
      stage('Deploy Code to UAT') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
