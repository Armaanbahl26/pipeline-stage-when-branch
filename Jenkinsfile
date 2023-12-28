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
        stage("Build main"){
            when{
                branch "main"
            }
            steps{
                echo "Building main"
            }
        }
    }
}
