pipeline {
    agent any
    stages {
        stage ('create stack') {
        steps {
            sh "aws cloudformation create-stack --stack-name sample-vpc-stack --template-body file://sample-vpc.json --region 'us-west-2'"
            }
        }
    }
}
