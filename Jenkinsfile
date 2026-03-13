pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/YOUR_USERNAME/YOUR_REPO.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
                sh 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo Tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                sh 'echo Deployment completed'
            }
        }
    }
}
