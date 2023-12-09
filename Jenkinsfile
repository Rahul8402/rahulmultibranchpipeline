pipeline {   
    agent any

    stages {   
        stage('sprint branch') { 
            steps { 
               sh 'echo "This is sprint application changes..."' 
            }
        }
     
        stage('test') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
