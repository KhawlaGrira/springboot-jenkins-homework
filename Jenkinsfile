pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/KhawlaGrira/springboot-jenkins-homework.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}