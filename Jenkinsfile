pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'gradlew clean build' 
            }
        }
    }
}
