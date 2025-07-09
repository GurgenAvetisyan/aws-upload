# 📦 aws-upload

A simple and efficient utility for uploading files to **Amazon S3** using the AWS SDK. This project helps you securely and easily upload single or multiple files to your AWS S3 buckets from a Node.js environment.

---

## 🚀 Features

- ✅ Upload files to Amazon S3 with ease
- 🔒 Secure AWS credential handling via environment variables
- 📁 Support for single or multiple file uploads
- ⚙️ Configurable S3 bucket, region, and access settings
- 🧩 Easily integratable into existing Node.js applications

Replace the placeholder values in your config.js file:

// config.js
module.exports = {
  AWS_ACCESS_KEY_ID: 'XXXXXXXXXXXXXXXXX',
  AWS_SECRET_ACCESS_KEY: 'XXXXXX/XXXXXXXXXXXXXXXXXXXXXXXXXX',
  AWS_REGION: 'eu-north-1',
  AWS_BUCKET_NAME: 'touristic',
};

📦 Dependencies
aws-sdk
