pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building with Maven...'
                sh 'mvn clean package'  // Assumes Maven is installed
            }
        }
        stage('Unit Tests') {
            steps {
                echo 'Running JUnit tests...'
                sh 'mvn test'
            }
        }
        // Add other stages here (as per your task requirements)
    }
}