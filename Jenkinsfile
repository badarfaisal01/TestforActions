pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/badarfaisal01/TestforActions.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run App') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
