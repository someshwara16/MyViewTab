pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo 'Hello World'
                bat 'atlas-compile'
            }
        }
       stage('Package') {
            steps {
                echo 'Hello World'
                bat 'atlas-package'
            }
        }
       stage('Deploy') {
            steps {
                echo 'Hello World'
		bat 'atlas-install-plugin --username jiraUsername--password jirapassword --server localhost --http-port 8080 --plugin-key com.atlassian.jira.jira-api --context-path ""'
            }
        }
    }
}