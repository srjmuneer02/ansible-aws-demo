# ansible-aws-demo


```
git clone https://github.com/srjmuneer02/ansible-aws-demo.git
aws cloudformation create-stack --stack-name myteststack01 --template-body file://cf-ec2.json --parameters ParameterKey=Vpc,ParameterValue=vpc-7aa04f1c  ParameterKey=EC2KeyName,ParameterValue=Ubuntu-12-Aug ParameterKey=Subnetid,ParameterValue=subnet-2f10bf74 ParameterKey=AssignedRole,ParameterValue=
```
