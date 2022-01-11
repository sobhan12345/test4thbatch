pipeline {
    agent any
    stages{
        stage('code cloning'){
            steps {
                git credentialsId: 'd8235bc8-7cdd-4f9d-98fb-abaafef09626', url: 'https://github.com/sobhan12345/simple-app.git'
            }
        }
        stage('build'){
            steps{
                sh 'echo "hello world"'
            }
                
            }
        stage('storing nexus'){
            steps{
                sh 'echo "hello world"'
               
            }
        }
        stage('deploy'){
            steps{
                sh 'echo "hello world"'
            }
    }
    }
    }
