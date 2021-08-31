pipeline{
    agent any

    stages{
        stage('SCM checkout'){
            steps{
                git branch: 'main', credentialsId: '3a1e32b0-3814-47d0-a33e-3c6145b8f5a8', 
                    url: 'https://github.com/Jaypalsolanki123/JenkinsDemo/edit/main'
            }
        }
    }
}
