pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "Build sample-book-app.. "
            }
        }
        stage('deploy-dev') {
            steps {
                echo "Deployment triggered to DEV environemnt.. "
            }
        }
        stage('api-test-dev') {
            steps {
                echo "API Tests triggered against DEV environemnt.. "
            }
        }
        stage('deploy-stg') {
            steps {
                echo "Deployment triggered to STG environemnt.. "
            }
        }
        stage('api-test-stg') {
            steps {
                echo "API Tests triggered against STG environemnt.. "
            }
        }
        stage('deploy-prd') {
            steps {
                echo "Deployment triggered to PRD environemnt.. "
            }
        }
        stage('api-test-prd') {
            steps {
                echo "API Tests triggered against PRD environemnt.. "
            }
        }
    }
}