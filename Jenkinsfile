pipeline{
    agent any
    stages{
        stage("Build Master"){
            when{
                branch 'master'
            }
            steps{
                echo "Building master"
            }
        stage("Builid Dev"){
            when{
                branch 'dev'
            }
            steps{
                echo "Building Dev"
            }
        }
        }
    }
}
