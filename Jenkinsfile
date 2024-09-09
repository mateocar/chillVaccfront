pipeline{
    agent any
    stages{
        stage('build '){
            steps{
                echo 'hola estoy en el contenedor'
            }
        }
         stage('build container'){
            steps{
                sh "docker run -dp 127.0.0.1:3000:3000 chillvaccfront"
            }
        }
    }
}
