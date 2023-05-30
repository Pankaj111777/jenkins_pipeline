pipeline{
    agent{
        lable"server1"
    }
    tools{
        jdk 'java17'
        maven 'Maven3'
    }
    stages{
        stage{"cleanup Workspace"}{
            steps{
                cleanWs()
            }
        }
    }

    stages{
            stage{"cleanup Workspace"}{
                steps{
                    git branch:'main',
                }
            }
}