pipeline {
    agent any

    stages {
        stage('checout code') {
            steps{
                checkout scm

            }
        }
        stage('run python program') {
            steps {
                sh "python extract.py"

            }
        }
    }
}