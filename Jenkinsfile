pipeline {
    agent {
        docker {
            image 'node:23-apline'
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