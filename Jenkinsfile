pipeline {
    agent any
    tools{
        maven 'Maven'
    }

    stages {
        stage('build') {
            steps {
                sh 'mvn package'
            }
        }

    
    
 
        stage('test') {
            steps {
                sh 'mvn test'
            }
        }

    }    
}
