pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building the application'
            }i
        }
        stage('Test') {
            steps {
                echo 'Testing the application'
                sh 'java -version'
            }
        }
        stage("Deploy") {
            steps {
                echo 'Deploying the application'
            }
        }
    }
}
