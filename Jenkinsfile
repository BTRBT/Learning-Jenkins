pipeline {
    agent {
        docker {
            label 'windows'
            image 'node:23-alpine'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}