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
                sh 'date'
            }
        }
        stage('List the directory') {
            steps {
                sh 'dir'
            }
        }
    }
}