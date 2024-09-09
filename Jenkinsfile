pipeline{
    agent {
        dockerfile true
    }
    stages{
        stage('build container'){
            steps{
                sh "docker run -dp 127.0.0.1:3000:3000 chillvaccfront"
            }
        }
    }
}
