pipeline {
    agent any

    stages {
        stage('List the directory') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}