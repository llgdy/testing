pipeline {
    agent { docker { image 'maven:3.9.4-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
	    environment {
                HOME = '.'
            }
            steps {
                sh 'mvn --version'
            }
        }
    }
}