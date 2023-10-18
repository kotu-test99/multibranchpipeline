pipeline {   
    agent any

    stages {   
        stage('Sprint1 branch') { 
            steps { 
               sh 'echo "This is sprint1 branch"' 
            }
        }
     
        stage('Test') { 
            steps { 
               sh 'echo "test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
