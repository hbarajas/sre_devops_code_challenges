Task:
	● Create an API in Python that implements the specifications described below.
	● Provision a maching into AWS.
	● Deploy your code into it using IaC(CloudFormation and Terraform).
	● Make your application containerized

AWS Infraestructure:
 - EC2 Instance
 - ALB
 - Securty Groups
 - ASG


API Specs:
 - The API Should be able to (List, Add, Remove, Describe) Instances from the ALB
 - The API Should return a 200 code if the ALB status its healthy in json format
 - The API 
 - The API should contain below endpoints:
   * /healthcheck
   * /elb/<string:elb_name>