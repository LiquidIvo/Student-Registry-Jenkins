pipeline{
    agent any

    stages{
        stage("Install npm dependencies"){
            steps{
               bat "npm install"
            }
            stage("Run tests"){ {
                steps{
                    bat "npm test"
                }
            }
           
        }
    }
    
}