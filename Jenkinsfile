pipeline {
    agent any

    tools {
        maven 'Maven3'
        jdk 'java 21.0.7'
    }

    stages {

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

    }
}

