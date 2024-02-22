pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'yarn install'
            }
        }
        stage('Run') {
            steps {
                sh 'yarn start'
            } 
        }
    }
}
