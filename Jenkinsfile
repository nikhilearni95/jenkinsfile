pipeline {
    agent any

    stages {
        stage('Validate') {
            steps {
                echo 'Validating..'
                sh 'mvn validate'
            }
        }
        stage('Compile') {
            steps {
                echo 'Compiling..'
                sh 'mvn compile'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing..'
                sh 'mvn test'
            }
        }
        stage('Clean') {
            steps {
                echo 'Cleaning..'
                sh 'mvn clean'
            }
        }
        stage('Package') {
            steps {
                echo 'Packaging..'
                sh 'mvn package'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
