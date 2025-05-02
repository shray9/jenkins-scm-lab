pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo "Code cloned successfully."
            }
        }
        stage('Test') {
            steps {
                echo "Running test cases..."
                sh 'python test.py'
            }
        }
    }
}
