# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: SANJAY A
* **Register Number**: 212225040367
* **Date of Submission**: 19-11-2026

---

## Objective

The objective of this experiment is to understand how Amazon Elastic Block Store (EBS) provides persistent block-level storage for EC2 instances. This lab focuses on creating and attaching an EBS volume, formatting and mounting it on an EC2 instance, storing data, and verifying data persistence after instance reboot.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing EC2 instance (Amazon Linux 2 preferred)
* Basic knowledge of Linux commands

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Amazon EBS
* SSH Client (Terminal / PuTTY)

---

## Tasks Performed

### Task 1: Explore Amazon EBS

Explore the Amazon EBS service through the EC2 dashboard. Observe different volume types such as General Purpose SSD (gp2/gp3), Provisioned IOPS SSD, Throughput Optimized HDD, and Cold HDD.

---

### Task 2: Create an EBS Volume

Create a new EBS volume in the same Availability Zone as the EC2 instance. Choose an appropriate size and volume type.

---

### Task 3: Attach EBS Volume to EC2 Instance

Attach the created EBS volume to the running EC2 instance as an additional block device.

---

### Task 4: Format the EBS Volume

Connect to the EC2 instance using SSH and format the attached volume with a file system (for example, ext4).

---

### Task 5: Mount the EBS Volume

Mount the formatted volume to a directory in the EC2 instance (for example, /data or /mnt/ebs).

---

### Task 6: Store Data in EBS Volume

Create files and directories inside the mounted EBS volume and store sample data.

---

### Task 7: Verify Data Persistence

Reboot the EC2 instance and verify that the data stored in the EBS volume is still available after reboot.

---

## Workflow (Student Explanation)

1. Launch an EC2 instance in AWS and open the Amazon EC2 dashboard.

2. Create a new EBS volume by selecting the required volume type and storage size.

3. Attach the created EBS volume to the running EC2 instance.

4. Connect to the EC2 instance, format the EBS volume, and mount it to store data.

5. Create a sample file, reboot the EC2 instance, and verify that the stored data is still available.
---

## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume Created

<img width="1846" height="1020" alt="Screenshot 2026-11-19 151700" src="https://github.com/user-attachments/assets/9769d74a-680d-472b-8f45-a1cb06b70279" />


---

### Screenshot 2: EBS Volume Attached to EC2

<img width="1846" height="965" alt="Screenshot 2026-11-19 153654" src="https://github.com/user-attachments/assets/f6584962-a01d-4012-a4dd-f970d681beba" />

<img width="1850" height="956" alt="Screenshot 2026-11-19 154745" src="https://github.com/user-attachments/assets/55de03b8-6277-4879-a376-c39e4060b343" />

---

### Screenshot 3: Mounted Volume with Data

<img width="1842" height="1011" alt="Screenshot 2026-11-19 154027" src="https://github.com/user-attachments/assets/36cbd8ef-e538-4e2d-8f3b-6a602ef7c665" />

---

## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
