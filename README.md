# ARTH-TASK-3
TASK DESCRIPTION:
1.Create a key pair.
2.Create a security group.
3.Launch an instance using the above created key pair and security group.
4.Create an EBS volume of 1 GB.
5.The final step is to attach the above created EBS volume to the instance created in the previous steps.
To use AWS CLI, we need to download and install it on the top of Operating System with which we are working. So, after installing to check whether its successfully installed, use the command:
`` aws --version ``
Here, we need to add the Access-key and Secret-key provided by AWS while creating this IAM User. Also, along with this we need to mention the default output format and the region. Here, region I am using is Mumbai i.e. ap-south-1.
![10 1](https://user-images.githubusercontent.com/64473684/95850722-e5ecd800-0d6e-11eb-8b92-93c8d7f0b092.jpeg)
So, now creating a keypair :
--key-name is an option to give a name to our key.
