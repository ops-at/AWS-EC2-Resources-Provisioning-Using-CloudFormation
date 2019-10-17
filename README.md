
# AWS-EC2-Resources-Provisioning-Using-CloudFormation
 AWS EC2 Resources Provisioning using AWS-CloudFormation

+ Note:
-	If you are interested in following along and you have the AWS CLI URL<URL>https://aws.amazon.com/cli/</URL> installed and configured, you can create this CloudFormation stack with the following:


+ Command:

aws cloudformation create-stack --stack-name stackname \
  --template-body file:///path/to/your/cf.json \
  --parameters ParameterKey=KeyName,ParameterValue=keyname


+ Warning: this and the other commands in this blog post will create AWS resources that may cost you money. Behave accordingly.

+ To delete the stack (and the corresponding AWS Resources), you can run this:

 aws cloudformation delete-stack --stack-name stackname
