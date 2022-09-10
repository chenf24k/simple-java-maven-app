pipeline {
    agent any
     tools {
            maven 'LOCAL'
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}