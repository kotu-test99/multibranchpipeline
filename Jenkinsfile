pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               sh 'echo "This is master branch for testing"' 
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
