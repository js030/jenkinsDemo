pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '2022-06-07'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
       post {
        always {
             echo 'pipeline finished';
        }
    }
}
