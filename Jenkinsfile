pipeline {
    agent any
    stages{
        stage{
            steps{
                echo("build docker image")
                sh 'sudo docker build -t my-website.'

                echo("runing the container")
                sh 'sudo docker run -itd -p 8080:80 my-website'
            }
        }

        stage{
            steps{
                
            }
        }

    }

}