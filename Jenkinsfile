pipeline {
    agent any

    stages{
        stage ('Build Image'){
            steps{
                script{
                    dockerapp = docker.build("bennerleon/api-produto" , '-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}