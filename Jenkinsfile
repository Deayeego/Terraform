pipeline {
agent any 
  stages {
    stage('Build Repo') {
      steps {
        sh "aws cloudformation create-stack --stack-name diegoterraform --template-body file://ec2-instance.yaml --region 'us-east-1'"
      }
    }
  }

}
