pipeline {
    agent {
        docker { 
            label 'jenkins-agent'
            image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Build') { 
            steps {
                echo 'Building the application Release 0.0.2'
            }
        }
        stage('Test') { 
            steps {
                echo 'Running Tests Release 0.0.2'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying application Release 0.0.2'
            }
        }
    }
}
