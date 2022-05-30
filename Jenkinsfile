pipeline{
    agent {
        docker {
            image 'python:3.10.1-alpine'
        }
    }
    stages {
        statge('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}