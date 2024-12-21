pipeline {
    agent any
    stages {
        stage ('SCM checkout') {
            steps {
                script{
                     git credentialsId: 'github', url: 'https://github.com/kk-1595/Jenkins--mine.git'
                }
            }
        }
    }
}
