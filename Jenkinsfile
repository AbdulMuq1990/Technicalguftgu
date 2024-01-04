@Library('my-shared-library') _
pipeline {
    agent any
    
    stages {
        stage('Git Checkout') {
            steps {
                sh 'git clone https://github.com/AbdulMuq1990/Technicalguftgu.git'
            }
        }
        
        stage('Shared library stage') {
            steps {
                helloWorld() 
            }
        }
    }
}
