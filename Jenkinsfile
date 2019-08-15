pipeline {
    agent { docker { image 'python:3.5.1' } }
    stage('Deploy - Staging') {
            steps {
                echo 'hello'
            }
        }

        stage('Sanity check') {
            steps {
                input "Does the staging environment look ok?"
            }
        }

        stage('Deploy - Production') {
            steps {
                echo 'deploying to prod'
            }
        }
}
