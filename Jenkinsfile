pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Check out the code from the Git repository
                checkout scm
            }
        }
        stage('Pull Git Content') {
            steps {
                // Create a directory to store the Git content
                dir('my-folder') {
                    // Copy the Git repository content to the directory
                    cp -r source_directory/* destination_directory/
'
                }
            }
        }
    }
}
