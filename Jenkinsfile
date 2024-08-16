/* Requires the Docker Pipeline plugin */
pipeline {
    agent { kubernetes { image 'maven:3.9.8-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
