pipeline {
    tools {
        maven 'maven3'
        jdk 'jdk17'
    }
    agent any

    stages {
        stage('mvn compile') {
            steps {
                sh 'mvn compile'
            }
        }
    
        stage('mvn test') {
            steps {
                sh 'mvn test'
            }
        }
    
        stage('mvn package') {
            steps {
                sh 'mvn package'
            }
        }
    
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    
}
