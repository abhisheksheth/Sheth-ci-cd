pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/abhisheksheth/Sheth-ci-cd.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                // Add your build commands here
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Add your test commands here
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Add your deployment commands here
                echo 'Deploying...'
            }
        }
    }
}

