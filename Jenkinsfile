pipeline {
    agent {
            label 'AGENT-1'
        }
    // Build
    stages {
        stage('Build'){
            steps {
                script{
                    echo "TEST PIPELINE BUILD"
                }
            }

        }

        stage('Test'){
            steps {
                script{
                    echo "TEST PIPELINE TESTING"
                }
            }

        }

        stage('Deploy'){
            steps {
                script{
                    echo "TEST PIPELINE DEPLOYING"
                }
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