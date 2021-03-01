pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'python3 --version'
                sh 'echo "Build"'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo "Test"'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Deploy"'
            }
        }
    }
}
