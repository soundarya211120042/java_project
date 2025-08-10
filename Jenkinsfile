pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/soundarya211120042/java_project.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac src/Hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java -cp src Hello'
            }
        }
    }
}
