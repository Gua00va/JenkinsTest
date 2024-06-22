pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL} found on ${env.BUILD_URL}"
            }
        }
    }
}
