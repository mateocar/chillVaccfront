pipeline{
    agent any
    stages{
        stage('build container'){
            steps{
                sh "docker build --tag chillVaccfront ."
            }
        }
    }
}
