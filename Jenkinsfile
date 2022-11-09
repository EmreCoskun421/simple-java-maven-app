pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'mvn package'
            }
        }

    }
    
    stages {
        stage('test') {
            steps {
                sh 'mvn test'
            }
        }

    }    
}
