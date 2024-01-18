pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout your source code from version control (e.g., Git)
                git 'https://github.com/mahab1/project.git'
            }
        }

        stage('Build') {
            steps {
                // Build your project (e.g., Maven)
                sh 'echo test'
            }
        }

        stage('Test') {
            steps {
                // Run tests (customize based on your project)
                sh 'echo subhani'
            }
        }

        stage('Deploy') {
            steps {
                // Deployment steps (customize based on your needs)
                echo 'Deploying...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! This is where you might trigger further actions.'
        }
        failure {
            echo 'Pipeline failed! Handle failure scenarios here.'
        }
    }
}
