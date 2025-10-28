pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ry-wong/learn-cicd.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
