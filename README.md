In this project, I built a simple and secure AWS architecture using: Application Load Balancer (ALB), Network Load Balancer (NLB), two EC2 instances, target groups, and security groups.

The goal was to send all traffic through the load balancers instead of accessing the EC2 instances directly. My mission was to ensure that traffic flows only through the load balancers and to block any direct access to the servers.

### Security Steps:
- SSH access is allowed only from my IP address.  
- EC2 instances do NOT allow public HTTP access.  
- EC2 instances only accept traffic from the ALB and NLB.  
- Load balancers allow public HTTP traffic.
