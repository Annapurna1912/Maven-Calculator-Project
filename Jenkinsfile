pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Annapurna1912/Maven-Calculator-Project.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

