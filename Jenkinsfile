pipeline {
    agent any
    parameters {
        string(name: 'GREETING', defaultValue: 'Hello', description: 'The greeting message')
        choice(name: 'BRANCH', choices: ['master', 'dev'], description: 'Branch to build')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // Here you can find the commands that build your application, such as mvn clean install
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying..'
                // Application deployment scripts
            }
        }
            stages {
        stage('Greeting') {
            steps {
                stage('Example') {
            steps {
                echo "${params.GREETING}, we are building the ${params.BRANCH} branch."
            }
        }
    }
}
            }
