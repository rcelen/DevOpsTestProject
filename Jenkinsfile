pipeline{
    agent any
    stages{
        stage("docker compose"){
            steps{
                
                sh 'docker compose BaseApp/docker-compose.yml up -d'
                sh 'docker compose ps'
            }
        }
    }
}