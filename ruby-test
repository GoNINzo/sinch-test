/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'ruby:3.3.4-alpine3.20' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
