pipeline{
    agent any
    stages{
        stage("docker compose"){
            steps{
                
                sh 'docker compose up -d'
                sh 'docker compose ps'
            }
        }
    }
}