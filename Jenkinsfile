pipeline {
    agent any

    stages {
    
            
                
        stage('Test') {
            steps {
                parallel(
                    a:{
                        echo "This is branch a"
                    },
                    b:{
                        echo "This is branch b"
                    }
                )
            }
        }
        stage('Build'){
            steps{
                echo "Build ${JOB_NAME}"
            }
        }
        stage('Deploy'){
            steps{
                echo "Deploy ${JOB_NAME} Hey ManpreetK Hey Sneh Hey Tinku Jiya"
            }
        }
     
    }
}

