pipeline {
    agent any
    
    tools {
        maven 'Maven'
    }

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat 'mvn -Dmaven.repo.local=C:\\mavenrepo clean compile'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn -Dmaven.repo.local=C:\\mavenrepo test'
            }
        }

    }
}
