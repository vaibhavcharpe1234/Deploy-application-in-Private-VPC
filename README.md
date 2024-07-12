Deploy application in Private VPC 🎉


![vpc-example-private-subnets](https://github.com/vaibhavcharpe1234/Deploy-application-in-Private-VPC-/assets/68227113/652b8fc9-bf8e-44c7-b2b9-33fd23ab1a02)

VPC with public-private subnets in Production

1.	Create VPC in ap-southeast-2 region
2.	Create two public subnets in different availability zones 
3.	Create two private subnets in different availability zones 
4.	Create internet gateway and attach it to the VPC
5.	Create NAT gateways in public subnets 
6.	Create autoscaling  group to launch instances in Private subnets
7.	Create load balancer to distribute traffic among multiple servers
8.	Verify application on browser by load balancer DNS

