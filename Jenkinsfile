pipeline {
    agent {
            label 'AGENT-1'
        }
    // Build
    stages {
        stage('Build'){
            steps {
                echo "TEST PIPELINE BUILD"
            }

        }

        stage('Test'){
            steps {
                echo "TEST PIPELINE TESTING"
            }
        }

        stage('Deploy'){
            steps {
                echo "TEST IS DEPLOYING"
            }
        }
    }

    post {
        always {
            echo 'PIPELINE STATUS'
            deleteDir()
        }
        success {
            echo 'PIPELINE SUCCESS'
        }
        failure {
            echo 'PIPELINE FAILURE'
        }
    }
}