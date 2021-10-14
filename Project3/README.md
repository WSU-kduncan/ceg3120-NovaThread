# Part 1 

1. ![VPC set up](Images/VPC.jpg)

2. ![Subnet Creation](Images/Subnet.jpg)

3. ![gateway set up](Images/gateway.jpg)

4. ![Setting up Route Table](Images/RoutingTable.jpg)

5. ![Select The Security Group](Images/SelectSecurityGroup.jpg)


# PART 2
## EC2 Instances

1.
![AMI selection](Images/AMI.jpg)
2. I attached the VPC to the instance by using the LaunchInstanceWizard found on the VPC management Console page

3. There will be an automatically generated Public IPv4 address for the new instance. I didn't add a specific one because I don't think I need too, its just simpler that way.

4. I continued on with the LaunchInstanceWizard found on the VPC management console page and added 12gb of storage, the default amount is 8.
![Adding Storage](Images/Storage.jpg)

5. Added a tag for the instance using the LaunchInstanceWizard.
![sample instance details](Images/Tag.jpg)

6. Associated the previously created security group to the instance.
![sample instance details](/Images/SecurityGroup.png)

7. Elastic IP reserved, I had to click on the instance and associate a new Elastic IP with it. I added the tag Short-EIP.
![Elastic IP](/Images/ElasticIP.jpg)

8. ![Instance Screenshot](/Images/InstanceScreenshot.jpg)

9. just type sudo hostname "name you want" I did "Short-AMI" since there isn't anything in there that I want to make a backup of I didn't. If it was something important I would have though.

10. I cannot believe it. I deleted my instance from AWS and forgot to take a snipit picture of me inside the vm. I did the write up after finishing the entire Project.