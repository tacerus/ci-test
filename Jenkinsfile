pipeline {
    agent { docker { image 'registry.suse.com/bci/python:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}
