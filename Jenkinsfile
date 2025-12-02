pipeline {
    agent any

    tools {
        maven 'Maven3'
        jdk 'java17'
    }

    stages {

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

    }
}

