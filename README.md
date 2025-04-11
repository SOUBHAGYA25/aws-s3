# 📦 S3 Event Tracker with Real-Time Notifications

This project monitors file uploads, deletions, and overwrites in an Amazon S3 bucket and sends real-time notifications using AWS Lambda and SNS. It is designed to demonstrate knowledge of AWS services like S3, Lambda, SNS, and IAM — perfect for cloud engineering portfolios.

---

## 🚀 Features

- ✅ Detects **file uploads**, **deletions**, and **overwrites** in S3
- ✅ Sends **email notifications** with event details
- ✅ Uses **AWS Lambda** to process events
- ✅ Sends notifications via **AWS SNS**
- ✅ Easy to deploy and extend

---

## 🧠 Architecture

```text
User Action (Upload/Delete/Overwrite)
          ⬇
      Amazon S3 Bucket
          ⬇
Triggers AWS Lambda Function
          ⬇
Sends Notification via Amazon SNS
          ⬇
    Email Notification to User
