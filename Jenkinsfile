pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                branches: [[name: 'main']],
                git 'https://github.com/minhtrannn/jenkins-github.git'
            }
        }
    }
}