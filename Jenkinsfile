pipeline {

    agent any

    stages {

        stage('Check Java Version') {
            steps {
                bat 'java -version'
            }
        }

        stage('Compile Program') {
            steps {
                bat 'javac PrimeNumber.java'
            }
        }

        stage('Run Program') {
            steps {
                bat 'java PrimeNumber'
            }
        }

    }
}
