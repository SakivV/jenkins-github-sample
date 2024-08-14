pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is build phase'
                // Example: Run a build script
                // sh './build.sh'
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
                echo 'Deploying...'
                // Example: Deploy to production
                // sh './deploy.sh'
            }
        }
    }
}
