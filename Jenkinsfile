pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Building application"
                    ls -lah
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing the application"
                echo "server space check"
                sh label: '', script: 'df -h'
            }
        }
    }
}
