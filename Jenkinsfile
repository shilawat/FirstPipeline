pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
                sh 'java --version'
                sh 'echo "This is a first Jenkins file"'
                sh 'echo "Hello Jenkins"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    sleep 30
                '''
            }
        }
    }
}