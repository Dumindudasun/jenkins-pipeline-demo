pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                echo 'Cleaning workspace...'
            }
        }
        stage('System Info') {
            steps {
                bat 'hostname'
                bat 'ipconfig'
            }
        }
        stage('Finish') {
            steps {
                echo 'Job completed successfully!'
            }
        }
    }
}
