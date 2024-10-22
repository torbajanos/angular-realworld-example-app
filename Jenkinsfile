pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                build elso
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
