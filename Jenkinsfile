pipeline {
    agent {
        label "AGENT-1"
    }
    options {
        timeout(time: 5, unit: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
                echo "this is pipeline"
            }
        }
        stage('Test') {
            steps {
                echo "this is pipeline stage 2"
            }
        }
        stage('Deploy') {
            steps {
                echo "this is pipeline stage 3"
            }
        }
    }
}