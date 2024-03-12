pipeline {
    agent any

    stages {
        stage('Install Nginx') {
            steps {
                script {
                    // Update package repositories
                    
                    // Verify Nginx installation
                    sh 'nginx -v'
                }
            }
        }
    }
}
