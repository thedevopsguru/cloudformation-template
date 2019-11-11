# cloudformation-template
## AWS CloudFormation Templates

Write a CloudFormation template to do the following:

- Create an AutoScaling group
  - Each EC2 instance should have a Name tag unique to the instance and a ClusterName tag shared among the AutoScaling group
- Allow all outbound traffic, but only inbound traffic on port 9000
- Create an association that executes a command on the host when it is brought up

This CloudFormation Template should take the following input parameters

- The Instance type (i.e. t2.micro)
- The number of instances in the autoscaling group
- The name for the cluster
- The port to open (default to 9000)
