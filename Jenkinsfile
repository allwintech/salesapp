pipeline {
    agent any
    stages {
        stage('code-review') {
            steps { 
                echo 'code review in-progress..'
            }
        }
        stage('Build') {
            steps {
                echo 'Hello, Building'
                sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello, Testing'
                sh 'java -version'
            }
        }
    }
}
