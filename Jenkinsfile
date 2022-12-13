pipeline {
    agent any
    stages{
        stage{
            steps{
                echo("build docker image")
                sh 'docker build -t webapp .'

                echo("runing the container")
                sh ' docker run -itd -p 80:80 webapp'
            }
        }

        stage{
            steps{
                
            }
        }

    }

}
