pipeline {
    agent { dockerfile true }
    stages {
        stage('Tomcat') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
