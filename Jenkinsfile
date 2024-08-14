pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is build phas-2'
            }
        }
        stage('Test') {
            steps {
                echo 'Test phase-1'
                // Example: Run tests
                // sh './run-tests.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Phase-1'
                // Example: Deploy to production
                // sh './deploy.sh'
            }
        }
    }
}
