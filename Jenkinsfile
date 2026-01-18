pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build started'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                sh 'exit 1'   // ❌ This forces failure
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying app'
            }
        }
    }
}
