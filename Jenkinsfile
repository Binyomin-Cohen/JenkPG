pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                input 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo \'Deploying\''
            }
        }
    }
}
