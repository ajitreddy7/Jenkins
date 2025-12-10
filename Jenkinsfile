pipeline{
    agent any
    stages{
        stage('build docker image'){
            steps{
                bat 'docker build -t ajith .'
            }
        }
        stage('run docker image'){
            steps{
                bat 'docker run ajith'
            }
        }
    }
}