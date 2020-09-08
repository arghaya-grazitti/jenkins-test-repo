pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                touch filename
                echo "raj" >> filename
                cat filename
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
