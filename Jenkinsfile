pipeline {
    agent any
    stages {
        stage('java') {
            steps {
                sh 'java --version'
            }
        }
        
        stage('folders list') {
            steps {
                sh 'ls /'
            }
        }
        stage('home') {
            steps {
                sh 'ls /home'
            }
        stage('pwd') {
            steps {
                sh 'pwd'
            }
        }
    }
}
