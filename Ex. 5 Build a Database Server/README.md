# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: SANJAY A
* **Register Number**: 212225040367
* **Date of Submission**:20-11-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

1. Launch an EC2 instance in AWS and configure the required instance type, operating system, and security group.

2. Connect to the EC2 instance using SSH and update the system packages.

3. Install a Database Management System (DBMS) such as MySQL or MariaDB on the EC2 instance.

4. Configure the database server, create a sample database, and create a user with appropriate permissions.

5. Verify the database server connectivity by connecting to the database and executing basic SQL queries.
---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1845" height="1020" alt="Screenshot 2026-11-20 151710" src="https://github.com/user-attachments/assets/9e4c08e0-720e-4821-bb2b-58df6a9d31ce" />


---

### Screenshot 2: Database Service Running

<img width="1843" height="1017" alt="Screenshot 2026-11-20 152949" src="https://github.com/user-attachments/assets/08109339-7e59-490c-b32c-241574d52040" />

---

### Screenshot 3: Sample Database and Table

<img width="1138" height="686" alt="Screenshot 2026-11-20 161825" src="https://github.com/user-attachments/assets/63c1e9eb-e802-40dc-9fea-d15cf15b6021" />


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
