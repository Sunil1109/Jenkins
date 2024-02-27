pipeline {
    agent any

    environment {
        NAME = "test env"
    }

    stages {
        stage('Build') {
            steps {
                sh 'sleep 10'
            }

            echo "Build"

        }
        stage('Test') {
            steps {
                sh """
                    #!/bin/bash
                    ls -lrt
                    sleep 5

                """
            }

            echo "Test"

        }
        stage('Deploy') {

            echo "Deploy"

        }
    }
}