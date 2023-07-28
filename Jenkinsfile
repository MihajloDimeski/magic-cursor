pipeline {
    agent any
    tools {
        nodejs "Node"
    }
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
