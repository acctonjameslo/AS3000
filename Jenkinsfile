pipeline {
    agent any
    
    stages {
        stage('Compile') {
            steps {
                echo 'Hi, this is AS3000, sample test'
            }
        }
            
        stage('Deploy') {
            steps {
                input('Do you want to proceed?')    
            }
        }
            
        stage('Test') {
            when {
                not {
                    branch "master"
                }
        }
            steps {
                echo "Test in progress"
            }
        }
    }
    
    
}
