pipeline {
    agent any
    
    stages {
        stage('One') {
            steps {
                echo 'Hi, this is AS3000, sample test'
            }
        }
            
        Stage('Two') {
            steps {
                input('Do you want to proceed?')    
            }
        }
            
        stage('Three') {
            when {
                not {
                    branch "master"
                }
        }
            steps {
                echo "Hello"
            }
        }
    }
    
    
}
