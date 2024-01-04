@Library('my-shared-library') _				# _ means everything just like * we mention to call all files.
pipeline {
    agent any
    
    stages {
        stage('Git Checkout') {
            steps {
                sh 'git clone '
            }
        }
        
        stage('Shared library stage') {
            steps {
                helloWorld()	         #mention name of the file which we created in vars folder, don’t mention function name in the file 
            }
        }
    }
}
