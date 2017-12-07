pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               echo 'This is a minimal pipeline.'     
                steps {
                    build 'github org/Repo1/master'
                }
            }
        }
    }
}
