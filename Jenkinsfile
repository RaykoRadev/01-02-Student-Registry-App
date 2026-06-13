pipeline{
    agent{
        label any
    }
    stages{
        stage("Install dependeces"){
            steps{
                bat 'npm install'
            }
        }

        stage("Start the tests"){
            steps{
                bat 'npm test'
            }
        }
    }

}