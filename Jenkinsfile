pipeline{
    agent any

    stages{
        stage("Install npm dependencies"){
            steps{
               bat "npm install"
            }
            stage {
                steps{
                    bat "npm test"
                }
            }
           
        }
    }
    
}