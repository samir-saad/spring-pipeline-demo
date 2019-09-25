pipeline {
    agent { node { label 'maven' }}
    
    stages {

        stage('Build and Test') {
            steps {
                sh 'mvn clean package'
            }
        }
    } 
}