 pipeline {
        agent any{
            
                stages {
                    stage('Checkout code') {
                        steps {
                              checkout([$class: 'GitSCM', branches: [[name: "*/main"]], 
                              userRemoteConfigs: [[credentialsId: "275c98cf-a077-4d88-8aca-4c9b3b6362b7", url: "https://github.com/pradeepbrucelee/Harsha-app.git"]]])
                    sh 'pwd; ls -lrt'        
                }
            }
        }
    }

}
