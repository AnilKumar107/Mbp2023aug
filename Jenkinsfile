pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact for project samplewebapp"
			   """
               
           }
       }
       stage('Reading branch wise')
       {
       when
       {
       branch "feature*"
       }
       steps
       {
       echo " It is only for the Feature branch"
       }
       }

       stage('Deploy Code') {
	   
          steps {
               sh """
               echo "Deploying  the Code"
			   """
               
          }
      }
      }
      }
