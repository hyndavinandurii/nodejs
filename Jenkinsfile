pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'npm test'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'node server.js'
         }

     }
  
   	}

   }
