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
           sh 'npm run'
           echo 'tested'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'node server.js'
         }

     }
  
   	}

   }
