//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { node { label 'agent' } }
    stages {
        stage('Deploy') {
            steps {
                echo "Deploying...."
            }
        }
        
    }

    post { 
        always { 
            echo 'cleaning up workspace'
            deleteDir()
        
        }
    }
}

