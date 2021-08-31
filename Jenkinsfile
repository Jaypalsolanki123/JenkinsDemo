pipeline{
    agent any

    stages{
        stage('SCM checkout){
            steps{
                git branch: 'main', credentialsId: 'github', url: 'https://github.com/Jaypalsolanki123/JenkinsDemo'
            }
        }
    }
}
