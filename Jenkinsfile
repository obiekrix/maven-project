pipeline {
    agent any

    stages {
        stage('Run maven proj') {
            steps {
                bat 'mvn clean package'
            }
        }
        stage('List the directory') {
            steps {
                bat 'dir'
            }
        }
    }
}