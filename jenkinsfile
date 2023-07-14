pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the project"'
                sh 'mvn clean install' // Replace with your build commands
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests"'
                sh 'mvn test' // Replace with your test commands
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying the project"'
                // Add your deployment commands here
            }
        }
    }
}
