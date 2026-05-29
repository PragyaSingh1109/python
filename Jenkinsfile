pipeline {
    agent any
    triggers {
        pollSCM 'H/2 * * * *'
    }
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from Git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
