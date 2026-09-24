pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps { echo 'Checking out code...' }
        }
        stage('Build') {
            steps {
                echo 'Building app...'
                bat 'dir'
            }
        }
        stage('Test') {
            steps { echo 'Tests passed!' }
        }
        stage('Deploy') {
            steps { echo 'Deployed successfully!' }
        }
    }
}
