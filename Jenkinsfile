pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/badarfaisal01/TestforActions.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                echo 'Installing dependencies...'
                // Add actual commands here
            }
        }

        stage('Run App') {
            steps {
                echo 'Running the app...'
                // Add run commands here
            }
        }
    }
}
