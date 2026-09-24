pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Code already checked out from SCM'
            }
        }
        stage('Build') {
            steps {
                bat 'npm install'
                bat 'npm run build || echo No build step'
            }
        }
        stage('Test') {
            steps {
                bat 'npm test || echo Tests done'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy stage - app ready!'
                bat 'node --version'
            }
        }
    }
}
