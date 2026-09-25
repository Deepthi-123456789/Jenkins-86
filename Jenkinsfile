pipeline{
    agent{
        node{
            label 'agent1'
        }
        
    }
    stages{
        stage('build'){
            steps{
                echo "build"
            }
        }
        stage('test'){
            steps{
                echo "test"

            }
            
        }
        stage('deploy'){
            steps{
                echo "deploy"
            }
        }
    }
}