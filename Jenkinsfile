pipeline {
    agent none
    stages {
        stage('build node') {
	    agent { docker { image 'node:16.13.1-alpine' } }
            steps {
                sh 'node --version'
            }
        }
	stage('build go') {
	    agent { docker { image 'golang:1.17.5-alpine' } }
            steps {
                sh 'go version'
            }
        }
    }
}
