pipeline {
    agent any
    parameters{
        string(name: 'NAME', defaultValue: 'Mr Fujaks', description: 'Who we should greet?')
    }

    stages {
        stage('Hello') {
            steps {
                echo "Hello ${params.NAME}"
                sh "docker -v"
            }
        }
    }
}