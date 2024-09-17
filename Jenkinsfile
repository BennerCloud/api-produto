pipeline {
    agent any

    stages{
        stage ('Build Image'){
            steps{
                script{
                    dockerapp = docker.build("bennerleon/hub" , '-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}