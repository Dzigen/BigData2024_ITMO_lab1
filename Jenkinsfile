pipeline {
    agent any

    stages {
        stage('unit-testing') {
            steps {
                echo "Stage 1!"
                echo "Hello World!"
            }
        }
        stage('building') {
            steps {
                echo "Stage 2!"
            }
        }
        stage('pushing to dockerhub') {
            steps {
                echo "Stage 3!"
            }
        }
    }
}        