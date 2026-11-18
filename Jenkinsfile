pipeline {
    agent any

    stages {
        stage('Checkout Info') {
            steps {
                echo "Building branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Build') {
            steps {
                echo 'Building Manufacturing Resource Management System module...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
