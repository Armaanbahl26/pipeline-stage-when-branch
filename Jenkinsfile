pipeline{
    agent any
    stages{
        stage("Build dev"){
            when{
                branch "dev"
            }
            steps{
                echo "Building dev"
            }
        }
    }
}
