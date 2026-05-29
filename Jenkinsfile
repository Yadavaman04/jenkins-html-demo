pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Downloading source code'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                    cp AP.html /var/www/html/index.html
                '''
            }
        }
    }
}