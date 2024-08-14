pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is build phas-1'
            }
        }
        stage('Test') {
            steps {
                echo 'This is test phase'
                // Example: Run tests
                // sh './run-tests.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Phase'
                // Example: Deploy to production
                // sh './deploy.sh'
            }
        }
    }
}
