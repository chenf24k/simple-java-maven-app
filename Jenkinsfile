pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
            args '-v C:/APP/apache-maven-3.6.3/repository:/root/.m2'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}