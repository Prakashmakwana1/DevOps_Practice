pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Prakashmakwana1/DevOps_Practice'
            }
        }

        stage('Build') {
            steps {
                echo '🔧 Building the project...'
                // For example: npm install
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
                // For example: npm test
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying to server...'
                // For example: docker run or copy to server
            }
        }
    }
}
