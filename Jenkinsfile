pipeline {
    agent any
    stages {
        stage('Install') {
            steps {
                script {
                    withMaven(maven: 'maven-3.0.5', mavenSettingsConfig: 'maven-config3') {
                        sh "mvn install"
                    }
                }
            }
        }
    }
}


