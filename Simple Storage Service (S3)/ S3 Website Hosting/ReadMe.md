# 🌐 AWS S3 Static Website Hosting Project

This project demonstrates how to use **Amazon S3** to host a static website and manage object lifecycle using lifecycle rules. This implementation is done for **XYZ Corporation**, whose application requires publicly accessible file storage and efficient lifecycle management.

---

## 📘 Problem Statement

You work for **XYZ Corporation**. Their application requires a **storage service** that can **store files**, **publicly share them**, and also **host static websites**. Additionally, they want to optimize storage cost and data retention by implementing lifecycle policies.

---

## ✅ Tasks Performed

1. **Hosted a Static Website** using the existing S3 bucket:
   - Uploaded `index.html` as the main landing page.
   - Uploaded `error.html` as the error fallback page.
   - Enabled **Static Website Hosting** in S3.

2. **Added a Lifecycle Rule** to the bucket:
   - **Transition rule**: Move objects from **Standard** to **Standard-IA** after **60 days**.
   - **Expiration rule**: Automatically **delete objects after 200 days**.

---

## 📄 Project Documentation

📥 [View PDF with Screenshots](https://github.com/Vaishnavi-Golhar/AWS-Projects/blob/main/Simple%20Storage%20Service%20(S3)/%20S3%20Website%20Hosting/S3%20Website%20Hosting.pdf)

---

## 🛠️ Tools & AWS Services Used

- **Amazon S3**
- **S3 Static Website Hosting**
- **Lifecycle Rules**
- **AWS Management Console**

---

## 🙋‍♀️ Author

**Vaishnavi Golhar**  
🔗 [GitHub Profile](https://github.com/Vaishnavi-Golhar)  
📫 [vaishnavigolhar05@gmail.com](mailto:vaishnavigolhar05@gmail.com)

---

⭐ *If this helped you learn how to host static websites on S3, feel free to star the repo!*

