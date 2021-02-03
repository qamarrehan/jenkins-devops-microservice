// Declative
pipeline {
    agent { docker { image 'maven:3.6.3'} }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --versions'
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
