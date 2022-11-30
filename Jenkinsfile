pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola"
                echo $prueba
                pwd
                ls -lrt
                echo $password
                pwd
                uname
                docker ps
                hostname
                touch 1
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola mundo"
                '''
            }
        }
        stage('deployar') {
            steps {
                sh '''
                echo "hola mundo"
                '''
            }
        }
    }
}
