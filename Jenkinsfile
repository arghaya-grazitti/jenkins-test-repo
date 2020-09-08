pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                writeFile file: 'filename', text: 'Working with files the Groovy way is easy.'
                sh "echo 'raj' >> filename"
                sh 'cat filename'
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
