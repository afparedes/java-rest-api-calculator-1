pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/afparedes/java-rest-api-calculator-1.git'
                sh './mvnw clean compile'
            }
        }
        stage('Test') {
                    steps {
                        sh './mvnw test'
                    }
        }
    }
}
