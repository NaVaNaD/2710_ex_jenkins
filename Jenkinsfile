pipeline {
    agent any

    stages {
        stage('QA') {
            steps {
                sh 'python print_name.py'
            }
        }
        stage('Production') {
            steps {
                sh 'ls -a'
            }
        }
    }
}
