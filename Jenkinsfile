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

            

        }
        stage('Test') {
            steps {
                sh """
                    #!/bin/bash
                    ls -lrt
                    sleep 5

                """
            }

            

        }
        stage('Deploy') {
            steps {
                sh 'sleep 10'
            }
        }
    }
}