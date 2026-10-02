pipeline {
    agent any

    triggers {
        pollSCM('* * * * *')
    }

    stages {

        stage('Build') {
            steps {
                echo 'Build stage started'
                sh 'date'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage started now'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage started now'
            }
        }
    }
}
