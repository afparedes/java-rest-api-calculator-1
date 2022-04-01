pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/afparedes/java-rest-api-calculator-1.git'
                sh 'mvn clean compile'
            }
        }
        stage('Test') {
                    steps {
                        sh 'mvn test'
                    }
        }
    }
}
