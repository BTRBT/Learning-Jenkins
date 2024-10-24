pipeline {
    agent {
        docker {
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