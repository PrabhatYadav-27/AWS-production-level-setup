# AWS-production-level-setup

# In this project we will see how to create the production level deployment setup in aws 
# About the project
This will demonstrates how to create a VPC that we can use for servers in a production environment. To improve resiliency will deploy the servers in two Availability Zones by using an Auto Scaling group and an Application Load Balancer. For additional security, we deploy the servers in private subnets. The servers receive request through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency, we deploy the NAT gateway in both the availibility zones. 
