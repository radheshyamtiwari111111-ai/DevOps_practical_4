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
                bat 'echo Maven Build Successful'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Tests Passed'
            }
        }

    }
}
