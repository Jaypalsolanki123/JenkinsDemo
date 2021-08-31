pipeline{
    agent any

    stages{
        stage('SCM checkout'){
            steps{
               git credentialsId: '74ec2926-11d2-4268-a3ad-0495dfdeac93', 
                   url: 'https://github.com/Jaypalsolanki123/JenkinsDemo'
            }
        }
    }
}
