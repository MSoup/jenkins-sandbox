pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                eval 1+1
                which python
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}