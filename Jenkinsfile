pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'python app.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add commands to run tests here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment steps here
            }
        }
    }
}
