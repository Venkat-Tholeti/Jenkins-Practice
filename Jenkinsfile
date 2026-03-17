pipeline {
    agent {
            label 'AGENT-1'
        }

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
}