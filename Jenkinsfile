pipeline {
    agent {
        docker {
            image 'php:7.4.0-fpm-alpine'
        }
    }

    stages {
        stage ('Build') {
            steps {
                sh 'php --version'
            }
        }
    }
}