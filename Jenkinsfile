pipeline {
    agent { docker { image 'python:3.5.1'
                      args '--user root:root' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
