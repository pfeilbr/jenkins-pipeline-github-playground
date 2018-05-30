pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Test') {
            steps {
                echo "Testing ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }   
        stage('Deploy') {
            steps {
                echo "Deploying ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        } 
    }
}