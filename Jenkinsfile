pipeline {
agent any 
  stages {
    stage('Build Repo') {
      steps {
        sh "aws cloudformation create-stack --stack-name deayegoekscluster1 --template-body file://ec2-instance.yaml --region 'us-east-1'"
      }
    }
  }

}
