# Assignment 1

## 🌐 Deployed Link

http://13.63.116.161/

---

### 🔹 Website Output

![Website](home.png)

---

## 📸 Screenshots

### 🔹 EC2 Instance (Running)

![EC2 Instance](ec2.png)

---

### 🔹 User 1 (No Access to EC2)

![User No Access](ec2_no.png)

---

### 🔹 User 2 (Full Access to EC2)

![User Full Access](ec2_full.png)

---

## 👤 IAM Users Configuration

![IAM](iam.png)

### User 1:

* Username: `user-no-access`
* Permissions: No permissions assigned
* Result: Cannot access EC2 (Access Denied)

### User 2:

* Username: `user-full-access`
* Permissions: `AmazonEC2FullAccess`
* Result: Can view and manage EC2 instances

---
