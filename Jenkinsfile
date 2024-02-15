pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hell1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hell2') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
        always {
            emailext body: '', subject: '', to: 'skumar8084064@gmail.com'
        }
    }
}
