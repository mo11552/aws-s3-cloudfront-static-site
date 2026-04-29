# AWS Static Website Deployment (S3 + CloudFront)

## 📌 Overview
This project demonstrates hosting a static website using Amazon S3 and distributing it globally with CloudFront.

---

## 🚀 Technologies Used
- AWS S3
- AWS CloudFront
- HTML / CSS

---

## 🌐 Live Site
https://djdzwaq4wbe9y.cloudfront.net

---

## ⚙️ Architecture
- S3 bucket hosts static files
- Static website hosting enabled
- CloudFront distribution provides CDN and HTTPS access

---

## ▶️ Deployment Steps
1. Create S3 bucket
2. Upload website files
3. Enable static website hosting
4. Configure bucket policy for public access
5. Create CloudFront distribution
6. Set origin to S3 website endpoint
7. Configure default root object (`index.html`)

---

## 🎯 Key Features
- Scalable static hosting
- Global content delivery (CDN)
- HTTPS-enabled access via CloudFront

---

## 📌 Challenges & Fixes
- Resolved 403 Access Denied errors by updating bucket policy
- Fixed origin configuration issues in CloudFront
- Corrected encoding issues in HTML rendering

---

## 📌 Future Improvements
- Add custom domain (Route 53)
- Enable HTTPS with SSL certificate