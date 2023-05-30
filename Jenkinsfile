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

    
        stage{"cleanup Workspace"}{
            steps{
                git branch:'main',credentialsID: 'github', url: 'https://github.com/Pankaj111777/jenkins_pipeline'
            }
        }
}