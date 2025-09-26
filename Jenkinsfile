//global vars

pipeline{
    agent any
    //Environmnet vars - used in shell commands
    // options (pipeline)
    stages{
        stage("make a directory"){
            // options()
            //input(proceed yes, no)
            // error handling
            steps{
                sh "mkdir ~/jenkins-test"
            }
            //post actions (always, on failure, on skipped - archiving, clean ups, emails)
        }
        stage("Add a file"){
            steps{
                sh "touch ~/jenkins/test/file1.txt"
            }
        }
    }
    //post actions{}
}