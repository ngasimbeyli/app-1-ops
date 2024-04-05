pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // Here you can find the commands that build your application, such as mvn clean install
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                // Commands that run tests, such as mvn test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying..'
                // Application deployment scripts
            }
        }
    }
}
