In this project, I built a simple and secure AWS architecture using:
Application Load Balancer (ALB)
Network Load Balancer (NLB)
Two EC2 instances
Target Groups
Security Groups
The goal was to send all traffic through load balancers instead of accessing the EC2 instances directly
my misstion is to send trafftic only through load balancer and block any acess direclty to the server
secuirty setps :
SSH access is allowed only from my IP address
EC2 instances do NOT allow public HTTP access
EC2 instances only accept traffic from: ALB & NLB
Load balancers allow public traffic (HTTP)
