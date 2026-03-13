pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building project..."
                bat 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                bat 'echo Tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                bat 'echo Deployment completed'
            }
        }

    }
}
