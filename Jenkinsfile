pipeline{
    agent any
    stages{
        stage(build docker image){
            steps{
                sh docker build -t ajith .
            }
        }
        stage(run docker image){
            steps{
                sh docker run ajith
            }
        }
    }
}