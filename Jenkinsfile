pipeline {
    agent any

    stages {
        stage('1-Build') {
            step {
                sh '''
                    echo "Start of Stage Build"
                    echo "Building..."
                    echo "End of Stage Build"
                '''
            }
        }
        stage('2-Test') {
            step {
                sh '''
                    echo "Start of Stage Test"
                    echo "Testing..."
                    echo "End of Stage Test"
                '''
            }
        }
        stage('3-Deploy') {
            step {
                sh '''
                    echo "Start of Stage Deploy"
                    echo "Deploying..."
                    echo "End of Stage Deploy"
                '''
            }
        }
    }
}
