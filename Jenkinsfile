pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                docker ps
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}