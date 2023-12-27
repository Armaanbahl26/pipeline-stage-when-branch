pipeline{
    agent any
    stages{
        stage("Build Master"){
            when{
                branch "master"
            }
            steps{
                echo "Building master"
            }
        }
        stage("Build dev"){
            when{
                branch "dev"
            }
            echo "Building dev"
        }
    }
}
