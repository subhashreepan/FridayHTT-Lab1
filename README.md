# FridayHTT-Lab1

- The creation of the template started with the base network resource configurations, configuring vpc nameing MyVPC.
- Two subnets were created, one Public subnet accesible to all traffic and another Private subnet created for only one EC2 instance.
- Connected both subnets to MyVPC network.
- Assigned IP addreses in the range of 10.0.0.0/16 for VPC and for subnets (For Private subnet - 10.0.2.0/24, for public subnet - 10.0.1.0/24)
- Created Public and Private route table and route table association cponnected to MyVPC network.
- Created Internet gateway and resource attach gateway to connect IGW with MyVPC.
- Created a Public EC2 instance, Private EC2 instance and a JumpBox EC2 instance (for accessing Private EC2 instance), all these instances are connected to MyVPC network.
- Ran the template tin application composer in aws and created the resources in aws platform.
