pipeline {
    agent any

    stages {
        stage('install') {
            steps {
                bat 'mvn install'
            }
        }
        stage('execute') {
            steps {
                bat 'java -jar target/test.jar'
            }
        }
    }
}

