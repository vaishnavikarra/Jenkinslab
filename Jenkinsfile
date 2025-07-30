pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo "Building"'
                bat 'javac Hello.java'
                bat 'java Hello'
            }
        }
    }
}
