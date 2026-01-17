pipeline {
    agent any

    stages {
        stage('Cleanup Old Container') {
            steps {
                sh '''
                docker stop flask-app || true
                docker rm flask-app || true
                '''
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t flask-devops .'
            }
        }

        stage('Run Flask App') {
            steps {
                sh 'docker run -d -p 5000:5000 --name flask-app flask-devops'
            }
        }
    }
}
