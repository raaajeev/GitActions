pipeline { 
  
  agent any

   stages {
     
     stage('npm install') { 
            steps {
                sh 'npm install' 
            }
        }
        
//      stage('build app') { 
       
//         steps { 
//            sh 'fastlane ios build'           
//         }
//       }

     stage("Deploy application") { 
        steps { 
           sh 'echo "deploying application..."'
 	   sh 'fastlane ios release'
         }

     }
  
   	}

   }
