pipeline {
    agent any

    stages {
        stage('Validate') {
            steps {
                dir("Servicio/Curso-Microservicios"){
                    sh "docker build -t microservicio ."
                }
            }
        }
        
        
        stage('DBDeploy') {
            steps {
                sh "docker images"
            }
        }
    }
}