pipeline {
    agent any
triggers{
    pollSCM '*/5 * * * *'
}
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh '''
                echo "doing the build..."
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing..."
                sh '''
                echo "...tests go here..."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo "Delivery! Yeah!"
                sh '''
                echo "Performing delivery now"
                '''
            }
        }
        
    }
}
