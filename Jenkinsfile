pipeline {
    agent any
    stages {
        stage ('create stack') {
        steps {
            sh "aws cloudformation create-stack --stack-name sample-vpc-stack --template-body file://vpc.json --region 'us-west-2'"
            }
        }
    }
}
