pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Start app') {
            steps {
                sh 'npm start'
            }
        }
    }
}
