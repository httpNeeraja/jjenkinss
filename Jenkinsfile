pipeline{
    agent any
    stages{
        stage('test'){
            steps{
                sh' python3 sample.py'
            }
        }
        stage('deploy'){
            steps{
                echo 'deployment succesful'
            }
        }
    }
}