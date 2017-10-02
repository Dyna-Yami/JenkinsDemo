pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
				bat 'ant build-run'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..2'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}