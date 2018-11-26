pipeline {
    agent any

    stages {
        stage('Building the code') {
            steps {
                echo 'Building1..'
            }
        }
        stage('Test for date command') {
            steps {
                bat 'date'
            }
        }
        stage('List the directory') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}