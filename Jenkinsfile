pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Docker Compose Up') {
            steps {
                sh 'docker compose up -d'
            }
        }
    }
}
