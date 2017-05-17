pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh('mvn install')
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
