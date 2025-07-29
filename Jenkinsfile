pipeline{
    agent{
        label "jenkins-agent"
    }
    stages{
        stage("Cleanup Workspace"){
            steps{
                cleanWs()
            }

        }
        stage("Checkout from SCM"){
            steps{
                git branch: 'main', url: 'https://github.com/YuzheZhang0/DVWA'
            }
        }
        stage("Build Application"){
            
        }
    }
}