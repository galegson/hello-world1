pipeline {
    agent any
    tools {
        maven 'M2_HOME'    
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean'
                sh 'mvn install'
                sh 'mvn package'               
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
                sh 'pwd'
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
