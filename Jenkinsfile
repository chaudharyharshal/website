pipeline {
    agent any
    tools {
        maven "3.9.1"
    }
    stages {
        stage('Clean and Install') {
            steps {
               sh 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               sh 'mvn package'
            }
        } 
    }
}
