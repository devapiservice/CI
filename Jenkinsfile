pipeline {
    agent {
        docker { image 'tomcat' }
    }
    stages {
        stage('Tomcat') {
            steps {
                sh 'node --version'
            }
        }
    }
}
