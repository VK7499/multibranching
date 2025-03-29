pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('developer') { 
            steps { 
               sh 'echo "This is developer branch...."'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch............."'
            }
        }  
    }
}
