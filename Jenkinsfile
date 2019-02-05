pipeline {
    agent any

    stages {
        stage('Compile Stage') {
            steps {
               bat 'mvn clean compile'
            }
        }
        stage('Testing Stage') {
            steps {
                    bat 'mvn test'
            }
        }
        stage('Deployment Stage (WAR)') {
            steps {
                    bat 'mvn deploy'
            }
        }
    }
}
