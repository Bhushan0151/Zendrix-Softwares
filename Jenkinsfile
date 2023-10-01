pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Check out the code from the Git repository
                checkout scm
            }
        }
        
        stage('Pull Git Content to Folder') {
            steps {
                // Use 'sh' to run shell commands, replace 'your-folder' with the desired folder name
                sh 'mkdir -p your-folder'
                sh 'cp -r * your-folder'
            }
        }
    }
}
