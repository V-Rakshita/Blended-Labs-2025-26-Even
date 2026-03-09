# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: RAKSHITA V
* **Register Number**: 212224100049
* **Date of Submission**: 09.03.2026

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

(Write the steps you followed in your own words)

1. The user logged in to the Amazon Web Services console and explored volume types in Amazon Elastic Block Store through the Amazon EC2 dashboard.

2. A new EBS volume was created in the same Availability Zone as the EC2 instance with an appropriate size and volume type.

3. The created EBS volume was attached to the running EC2 instance as an additional block device.

4. The instance was accessed via SSH and the attached volume was formatted using the ext4 file system.

5. The formatted EBS volume was mounted to a directory and sample files were created to verify data storage and persistence after reboot.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume CreateD

<img width="1920" height="970" alt="Screenshot (775)" src="https://github.com/user-attachments/assets/f325de01-1a18-4814-91c9-76447884c32b" />


### Screenshot 2: EBS Volume Attached to EC2

<img width="1920" height="901" alt="Screenshot (776)" src="https://github.com/user-attachments/assets/5e475b77-f552-4088-922e-5b0f01076cc3" />



### Screenshot 3: Mounted Volume with Data

<img width="1920" height="897" alt="Screenshot (781)" src="https://github.com/user-attachments/assets/970799fe-3b14-4431-9c00-ec66c1921513" />


## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
