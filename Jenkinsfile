pipeline {
    agent { label 'windows' }


    
    environment {
        APP_NAME = "MyApp"
        ENVIRONMENT = "dev"
    }


    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'

            }
        
        }
        stage('Change') {
            steps {
                echo 'old change pushed!'

            }
        
        }
        stage('Print Info') {
            steps {
                echo "App Name: ${APP_NAME}"
                echo "Environment: ${ENVIRONMENT}"
            }
    }
}
