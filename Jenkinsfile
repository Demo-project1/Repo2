pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               echo 'This is a minimal pipeline.'  
            }
        }
                stage('Build1') {
                steps {
                    build 'github org/Repo1/master'
                    }
                }
    }
}
