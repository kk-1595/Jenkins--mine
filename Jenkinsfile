pipeline {
    agent any
    stages {
        stage ('SCM checkout') {
            steps {
                script{
                     git credentialsId: 'git-token', url: 'https://github.com/naresh26git/helm-node.git'
                }
            }
        }
