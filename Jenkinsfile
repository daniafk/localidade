pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pip install google-cloud-bigquery'
                sh 'python3 script2.py'
            }
        }
    }
}
