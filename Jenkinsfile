pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'javac Hello.java'
            }
        }
        stage('DisplayOutput') {
            steps {
                echo 'Output..'
                sh 'java Hello'
            }
        }
        
    }
}