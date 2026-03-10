pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building DevOps Project'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Successful'
            }
        }

    }
}
