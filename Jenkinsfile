pipeline {
    agent any

    stages {
        stage('Install Nginx') {
            steps {
                script {
                    // Verify Nginx installation
                    sh 'nginx -v'
                }
            }
        }
    }
}
