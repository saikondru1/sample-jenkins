pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out the source code...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                script {
                    echo 'Build complete!'
                }
            }
        }

        stage('Dev Deployment') {
            steps {
                echo 'Deploying to the development environment...'
                script {
                    echo 'Deployment to Dev complete!'
                }
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                script {
                    echo 'Tests passed!'
                }
            }
        }

        stage('Prod Deployment') {
            steps {
                echo 'Deploying to the production environment...'
                script {
                    echo 'Deployment to Prod complete!'
                }
            }
        }

        stage('Post Deployment Steps') {
            steps {
                echo 'Performing post-deployment steps...'
                script {
                    echo 'Post-deployment steps complete!'
                }
            }
        }
    }

    post {
        success {
            echo 'Build success
