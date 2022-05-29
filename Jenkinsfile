pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("nielbit/api-produto", '-f ./src/Dockerfile ./src')
                }
                
            }                
        }
    }
}
