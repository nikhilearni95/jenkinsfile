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
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
