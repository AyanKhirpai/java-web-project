pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn -DskipsTests clean package'
            }
        }
         stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
