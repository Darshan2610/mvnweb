pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Darshan2610/mvnweb.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        
    }
}
