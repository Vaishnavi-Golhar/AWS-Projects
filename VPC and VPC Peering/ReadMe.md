# 🌐 AWS VPC and VPC Peering Project

This project demonstrates how to set up **Amazon VPCs** for the **Production** and **Development** teams, establish **subnet architecture**, manage **internet access**, and configure **VPC Peering** between networks in AWS for secure and efficient communication.

---

## 📘 Problem Statement

You work for **XYZ Corporation**, which is undergoing an infrastructure expansion. You're tasked with designing and deploying isolated and well-architected **VPC environments** for the **Production** and **Development** teams and establishing secure **VPC peering** between them.

---

## ✅ Tasks Performed

### 🏭 Production Network

1. **Designed a 4-tier architecture**.
2. **Created 5 subnets**:
   - `app1` (Private)
   - `app2` (Private)
   - `dbcache` (Private)
   - `db` (Private)
   - `web` (Public)
3. **Launched EC2 instances** in each subnet and named them based on the subnet.
4. **Enabled internet access** for:
   - `dbcache` instance
   - Instances in the `app1` subnet
5. **Configured Security Groups and NACLs** for secure access and traffic filtering.

---

### 🧪 Development Network

1. **Designed a 2-tier architecture**.
2. **Created 2 subnets**:
   - `web`
   - `db`
3. **Launched EC2 instances** in each subnet and named them accordingly.
4. **Allowed internet access only to the `web` subnet**.
5. **Created a VPC Peering connection** between the **Production** and **Development** VPCs.
6. **Set up communication between the `db` subnets** of both VPCs using route tables and security groups.

---

## 📄 Project Documentation

📥 [View Full PDF Report with Steps and Screenshots](https://github.com/Vaishnavi-Golhar/AWS-Projects/blob/main/VPC%20and%20VPC%20Peering/VPC%20and%20VPC%20peering%20Project.pdf)

---

## 🛠️ Tools & AWS Services Used

- **Amazon VPC**
- **EC2 Instances**
- **Internet Gateway**
- **Route Tables**
- **NAT Gateway**
- **Security Groups**
- **Network ACLs**
- **VPC Peering**
- **AWS Management Console**

---

## 🙋‍♀️ Author

**Vaishnavi Golhar**  
🔗 [GitHub Profile](https://github.com/Vaishnavi-Golhar)  
📫 [vaishnavigolhar05@gmail.com](mailto:vaishnavigolhar05@gmail.com)

---

⭐ *If this project helped you or inspired you, feel free to give it a star!*

