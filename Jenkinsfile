pipeline {
    agent any

    stages {
        stage('checkout'){
        steps{
            script{
                checkout
            }
        }    
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
