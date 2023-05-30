pipeline{
    agent{
        label"server1"
    }
    tools{
        jdk 'java17'
        maven 'Maven3'
    }
    stages{
        stage{"Cleanup Workspace"}{
            steps{
                cleanWs()
            }
        }
    }

    
        stage{"Cleanup from SCM"}{
            steps{
                git branch:'main',credentialsID: 'github', url: 'https://github.com/Pankaj111777/jenkins_pipeline'
            }
        }
}