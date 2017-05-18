pipeline {
    agent any
    tools {
        maven 'mymvn'
    }
    stages {
        stage('test mvn') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('install') {
            steps {
                sh 'mvn clean install'
            }
        }        
    }
}
