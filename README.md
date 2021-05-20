# Cloud-Formation-for-Deploy-Scalability-

imagine a business has tasked you with deploying a prototype of a new application. The business has given you the following requirements:

Deploy this xxxx application in AWS.

Allow for simple scaling of the compute and database layers.

Use the following:

AWS EC2 to host the application.

AWS ELB to load balance public traffic.

AWS DynamoDB for the database.

Appropriately use public and private subnets.

Deployments should be easily repeatable.

Allow for the deployment of multiple environments (development, testing, and production).

Allow for deployment into any AWS Region.

As this is a prototype, multi-availability zone redundancy is not required.

When given a set of requirements, a good way to start planning is to draw a diagram of potential solutions. 
It's less costly to make a mistake on a diagram than after deploying infrastructure. Here is an example of a diagram that could be produced from these requirements:


![image](https://user-images.githubusercontent.com/58148717/119038308-957ad000-b978-11eb-9854-8fcc5cf1ae8d.png)


