pipeline {
    agent any
     tools {
            maven 'LOCAL'
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}