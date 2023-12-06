pipeline {   
    agent any

    stages {   
        stage('jenkins branch') { 
            steps { 
               sh 'echo "This is jenkins branch"' 
            }
        }
     
        stage('sprint2') { 
            steps { 
               sh 'echo "jenkins application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
