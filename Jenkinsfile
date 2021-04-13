pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
                sleep 10
            }
        }
      stage('Test') {
            steps {
                echo 'Hello Test'
                sleep 5
            }
        }
      stage('Deploy') {
            steps {
                echo 'Hello Deploy'
                pwd
            }
        }
        stage('Push') {
            steps {
                echo 'Hello push'
                sh 'docker ps'
            }
        }
    }
}
