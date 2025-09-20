pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch..chnage done"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch....change done"'
            }
        }  
    }
}
