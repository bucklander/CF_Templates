# AWS CloudFormation Stacks
This is a personal repo of my own customized CF stacks, probably themed around virtual networking.  

These templates will save you time by launching various network appliance instances in your AWS account with the following simultaneous tasks:  

* Right-size the EC2 instance, based on your bandwidth requirements  
* Give choice of either bundled or "bring your own license" AMIs from the AWS marketplace   
* Give choice to EC2 tenancy type & termination protection   
* Bootstrap the image with an existing SSH key pair  
* Allocate and assign an Elastic IP address to the instance  
* Create / assign an IAM instance policy (since they can't be assigned post-launch)  
* Create / assign a security-group (initially only permitting port 22/TCP inbound)  
* Disable the 'src/dst' check on the instance  
* Specify the existing VPC and public subnet to launch the instance  
* Enable instance status check alarm with auto restore if failure  


More Info: [AWS Cloudformation for NFV](http://the.vpn.center/2017/01/amazon-cloudformation-for-nfv.html)
