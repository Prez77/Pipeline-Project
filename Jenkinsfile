pipeline {
    agent any  // Runs on any available agent

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Prez77/Pipeline-Project.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add build commands (e.g., mvn package, npm install)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands (e.g., mvn test, npm test)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Add deployment steps (copy files, run scripts, etc.)
            }
        }
    }
}
