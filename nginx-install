pipeline {
    agent any

    stages {
        stage('Install Nginx') {
            steps {
                script {
                    // Update package repositories
                    sh 'sudo yum update -y'

                    // Install Nginx
                    sh 'sudo yum install -y nginx'

                    // Start Nginx service
                    sh 'sudo systemctl start nginx'

                    // Enable Nginx service to start on boot
                    sh 'sudo systemctl enable nginx'

                    // Verify Nginx installation
                    sh 'nginx -v'
                }
            }
        }
    }
}
