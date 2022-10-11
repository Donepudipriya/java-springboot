pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'build'
            }

        }
        stage('Test') {
            steps {
                echo 'Test'
            }

        }
        stage('Push to artifactory') {
            steps {
                echo 'Push to artifactory'
            }

        }
        stage('Deploy to dev') {
            steps {
                echo 'Deploy to dev'
            }

        }
        stage('Deploy to Test') {
            steps {
                echo 'Deploy to Test'
            }

        }
        stage('Deploy to stage') {
            steps {
                echo 'Deploy to stage'
            }

        }
        stage('Deploy to prod') {
            steps {
                echo 'Deploy to prod'
            }

        }

    }

        post {
            failure {
                echo 'Failed'
            }
            success {
                echo 'Success'
        
            }
            aborted {
                echo 'Aborted'
            }
            always {
                echo 'Always'
            }
        }
    }

