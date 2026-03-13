pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'main', 'https://github.com/Aiswaryaroy-S/devops-demo-app.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t devops-app .'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run -d -p 8081:80 devops-app'
            }
        }

    }
}
