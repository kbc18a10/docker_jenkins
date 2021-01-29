pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node hello.js'
            }
        }
    }
}