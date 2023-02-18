pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
              sh "aws configure set region us-west-2" 
              sh "aws configure set aws_access_key_id AKIA2SMREKDLDHQLG4VV"  
              sh "aws configure set aws_secret_access_key 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"
              sh "aws s3 cp Code/index.html s3://static-jenkins-17-23"
            }
        }
    }
}
