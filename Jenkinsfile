pipeline {
    agent any
    stages {
        stage('java') {
            steps {
                sh 'java --version'
            }
        }
        
        stage('show folders') {
            steps {
                sh 'ls /'
            }
        }
        stage('home') {
            steps {
                sh 'ls /home'
            }
        }
    }
}
