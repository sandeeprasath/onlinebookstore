pipeline {
    agent any
    stages{
    stage('Build') {
        steps{
            echo 'Building ...'
        }
        post{
            always{
                jiraSendBuildInfo site:'dallasdevopscasestudy.atlassian.net'
            }
        }
    }
    }

}
