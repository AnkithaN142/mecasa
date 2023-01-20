pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is Build'
            }
        }
         stage('Test') {
            steps {
                echo 'This is Test'
            }
        }
         stage('Deploy') {
            steps {
                echo 'This is Deploy'
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'cutie lovely pretty', subject: 'Testing', to: 'ankitharaj142@gmail.com'
        }
    }
}
