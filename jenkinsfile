pipeline {
    agent any

    stages {

        stage('Welcome home') {
            steps {
                echo 'Checking out source code...'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }

        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }

        stage('Package') {
            steps {
                sh 'mvn package'
            }
        }

        stage('Success') {
            steps {
                echo 'Build Completed Successfully!'
            }
        }

    }
}
