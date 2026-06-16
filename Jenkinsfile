pipeline {
    agent any

    stages {

        stage('Pull Code') {
            steps {
                echo 'Code Pulled Successfully'
            }
        }

        stage('Unit Test') {
            steps {
                echo 'Running Tests'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Building Docker Image'
            }
        }

        stage('Docker Push') {
            steps {
                echo 'Pushing Docker Image'
            }
        }
    }
}