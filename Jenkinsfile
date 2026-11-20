
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Check Python') {
            steps {
                bat 'python --version'
            }
        }

        stage('Check Git') {
            steps {
                bat 'git --version'
            }
        }

        stage('Build') {
            steps {
                echo 'Django Todo CI/CD Project Build Started!'
            }
        }
    }
}

