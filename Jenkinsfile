pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Terraform version') {
            steps {
                sh 'terraform version'
            }
        }
    }
}
