pipeline {
    agent any

    stages {
        stage('validate') {
            steps {
                echo 'Validating..'
                sh 'mvn validate'
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
