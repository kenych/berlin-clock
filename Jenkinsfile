pipeline {
    agent any
    tools {
        maven 'maven-3.5.0'
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
