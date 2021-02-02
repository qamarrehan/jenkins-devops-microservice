// Declative
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build"
            }
        }
        stage('Test') {
            steps {
                echo "Test"
            }
        }
        stage('Integration Test') {
            steps {
                echo "Integration Test"
            }
        }

    }

    post {
        always {
            echo 'Im awesome. I run alwayd'
        }
        success {
            echo 'Im awesome. I run on success'
        }
        failure {
            echo 'I run when you fail'
        }

    }
}
