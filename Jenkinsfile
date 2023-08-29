pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                branch: 'main',
                git 'https://github.com/minhtrannn/jenkins-github.git'
            }
        }
    }
}