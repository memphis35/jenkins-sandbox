pipeline {
    agent any
    stages {
        stage('Greetings') {
            steps {
                sh "echo Hello World"
            }
        }
        stage('Build') {
            steps {
                sh "./gradlew build"
            }
        }
    }
}
