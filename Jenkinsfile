pipeline {
    agent any
    stages {
        stage('Initialize') {
            steps {
                echo 'Starting the pipeline...'
            }
        }
        stage('Check System Info') {
            steps {
                powershell 'systeminfo'
            }
        }
        stage('Finish') {
            steps {
                echo 'Pipeline completed!'
            }
        }
    }
}
