pipeline {
    agent any
    
    stages {    
        stage('Lock Master Branch') {
             steps {
                 https://docs.github.com/en/rest/reference/repos#set-admin-branch-protection
             }
         }
        stage('Create issue') {
            steps {
               https://docs.github.com/en/rest/reference/issues#create-an-issue
            }
        }
        stage('Mention user') {
            steps {
               https://docs.github.com/en/rest/reference/issues#create-an-issue-comment
            }
        }
    }
}
