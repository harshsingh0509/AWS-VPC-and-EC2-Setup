# AWS-VPC-and-EC2-Setup
This repository outlines the steps followed to set up a secure AWS infrastructure with VPC, EC2 instances, and routing configurations.

## **Overview**
The project includes:
- VPC with public and private subnets.
- EC2 instances with proper security configurations.
- Security groups, network ACLs, and IAM roles for secure access.
- NAT Gateway and Internet Gateway for routing and internet access.
- Testing the setup for connectivity and security validation.

## **Steps Followed**

### **1. Design and Configure VPC**
- Created a VPC with custom IP ranges.
- Configured public and private subnets, route tables, and associated them.

### **2. Implement Network Security**
- Set up security groups and network ACLs to manage traffic.

### **3. Provision EC2 Instances**
- Launched EC2 instances in private and public subnets.
- Configured security groups and IAM roles for access control.

### **4. Configure Networking and Routing**
- Set up an Internet Gateway for public subnet access and a NAT Gateway for private subnet internet access.

### **5. SSH Key Pair and Access Control**
- Generated and used SSH key pairs for secure access.
- Applied IAM policies for resource access control.

### **6. Test and Validate the Setup**
- Verified EC2 connectivity and validated network rules.

## **Technologies Used**
- AWS VPC, EC2, NAT Gateway, Internet Gateway, IAM, Security Groups, Network ACLs.

## **Conclusion**
This project demonstrates creating a secure, scalable infrastructure on AWS for hosting applications with public and private access.
