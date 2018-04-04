pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build-step1'
            }
            {
                echo 'Build-step2'
            }
        }
        stage('Test') {
            steps {
                echo 'Test-step1'
            }
            {
                echo 'Test-step2'
            }
        }
    }
}
