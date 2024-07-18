pipeline {
    agent any

    stages {
        stage('Build1') {
            steps {
                echo 'Building..'
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
        stage("ECS")
        {
            steps {
                echo 'ECS...'
            }
        }
    }
}