pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build node') {
            steps {
                sh 'node --version'
            }
        }
    }
}
