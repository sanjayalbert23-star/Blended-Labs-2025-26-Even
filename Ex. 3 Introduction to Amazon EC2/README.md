<img width="578" height="586" alt="image" src="https://github.com/user-attachments/assets/5bc2ed41-183d-42df-ab78-7bc120bd6a9d" /># Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: SANJAY A
* **Register Number**: 212225040367
* **Date of Submission**: 18-11-2026

---

## Objective:

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

1. Open the AWS Management Console and navigate to the EC2 service.
2. Select an Amazon Machine Image (AMI) and choose a suitable EC2 instance type.
3. Launch a virtual server by configuring the required instance settings.
4. Connect to the EC2 instance and monitor its status.
5. Perform basic instance operations such as start, stop, and terminate.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1750" height="899" alt="AWS EC2 Instances Console View" src="https://github.com/user-attachments/assets/fa530ff0-8650-49a8-b677-94828018b780" />


---

### Screenshot 2: SSH Connection to Instance

<img width="1133" height="711" alt="Screenshot 2026-11-18 162315" src="https://github.com/user-attachments/assets/aba4a400-97d8-4e19-a460-ccbaad227783" />


---

### Screenshot 3: Instance Monitoring / Status

<img width="1764" height="892" alt="AWS EC2 System Log — SANJAY_A Account" src="https://github.com/user-attachments/assets/5dd3ed17-1aca-4932-879b-c94110e72f97" />

---

## Result 
Successfully launched and managed an Amazon EC2 instance, understood AMIs and instance types, connected to the virtual server, monitored its status, and performed basic operations such as start, stop, and terminate.
---

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
