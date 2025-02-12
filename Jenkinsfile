pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Anurag-Negi28/DemoCICD.git'
            }
        }
        stage('Build') {
            steps {
                echo "Building the project..."
                // Add build steps here (e.g., mvn package, npm install, etc.)
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                // Run tests here (e.g., sh 'npm test' or sh './run-tests.sh')
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying application..."
                // Deployment steps (e.g., Docker push, SCP commands, etc.)
            }
        }
    }
}
