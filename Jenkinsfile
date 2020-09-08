
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                //writeFile file: 'filename', text: 'Working with files the Groovy way is easy.'
                sh "echo 'raj' >> filename"
                sh 'cat filename'
                sh 'cat filename > testfile'
                sh 'cat testfile'
                sh 'touch abc'
                sh 'ls'
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
    post {
        always {
            cleanWs()
        }
    }
}
