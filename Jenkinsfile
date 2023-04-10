pipeline {
    agent any
    stages{
        stage('Test'){
            agent {
                docker {
                    image 'mcr.microsoft.com/dotnet/sdk:7.0'
                }
            }
            steps {
                echo 'Testing..'
            }
        }
    }
}