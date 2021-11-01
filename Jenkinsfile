pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mydockermaven"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
