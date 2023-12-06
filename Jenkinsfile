pipeline {   
    agent any

    stages {   
        stage('sprint2 branch') { 
            steps { 
               sh 'echo "This is sprint2 branch"' 
            }
        }
     
        stage('sprint2') { 
            steps { 
               sh 'echo "sprint2 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
