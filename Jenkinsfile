pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/mhassini/avec-maven.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
