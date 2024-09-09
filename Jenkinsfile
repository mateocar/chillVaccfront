pipeline{
    agent any
    stages{
        stage('build '){
            steps{
                echo 'hola estoy en la imagen '
                sh 'docker build --tag chillvaccfront .'
            }
        }
         stage('build container'){
            steps{
                echo 'estoy en el contenedor'
                sh 'docker run -dp 127.0.0.1:3000:3000 chillvaccfront' 
            }
        }
    }
}
