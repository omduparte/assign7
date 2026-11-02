pipeline {
    agent any
    stages {
        stage('Compile Java Program') {
            steps {
                sh 'javac hello.java'
            }
        }
        stage('Execute Application') {
            steps {
                sh 'java hello'
            }
        }
    }
}
