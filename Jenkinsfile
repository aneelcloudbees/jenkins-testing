pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sleep 300
                echo "Building on branch: ${env.BRANCH_NAME}"
                echo "Build number: ${env.BUILD_NUMBER}"
            }
        }
    }
}
