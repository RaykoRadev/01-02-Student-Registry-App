pipeline{
    agent{
        label "node"
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