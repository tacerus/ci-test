pipeline {
    agent {
        docker {
                image 'registry.suse.com/bci/python:latest'
                label 'docker' 
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh '$(hostname) && echo $(pwd) && ls -alR'
            }
        }
    }
}
