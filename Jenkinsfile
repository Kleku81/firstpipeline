Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { label 'slave' } {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}


