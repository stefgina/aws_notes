EC2 most popular AWS offering - Elastic Compute Service

bootstraping means launching commands when a machine starts
eg install updates, software, common files etc.

EC2 user script must run on root user
t2 is free-tier


![](ec2-instances.png)

C-instances: compute optimised
R-instances, X1, High Memory, z1: memory optimised
I-instances, d, h1: Storage optimised

ec2instances.info : can check all the info about instances

application not accessible (timeout) : security group issue


![](ports.png)
The logic is to use Security groups as Firewalls, limit IPs and Ports Inbound, and Outbound everything




