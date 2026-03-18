# AWS S3 Static Website

This project demonstrates the deployment of a static website using Amazon S3.  
It is my first hands-on project in AWS as part of my cloud learning journey.

---

## What I Did
- Deployed a static website on Amazon S3  
- Configured public access and bucket policy  
- Enabled Static Website Hosting  
- Uploaded HTML content and validated public access  

---

## Technologies Used
- **AWS S3**  
- **AWS IAM (basic concepts)**  
- **HTML**  

---

## Live Demo
http://dani-aws-web-123.s3-website.eu-south-2.amazonaws.com

---

## Result
A fully functional public static website hosted on AWS S3.

---

## What I Learned
- How to create and configure an S3 bucket  
- How to set bucket policies for public access  
- How to enable and use Static Website Hosting  
- How to make a website accessible from the internet  

---

## Project Structure
.
index.html
README.md

---

## How to Reproduce
1. Create an S3 bucket (with a unique global name).  
2. Disable “Block all public access”.  
3. Upload your website files (e.g., `index.html`).  
4. Enable **Static Website Hosting**.  
5. Add a bucket policy allowing public read access.  
6. Access the website using the S3 website endpoint.  

---

## Future Improvements
- Add CSS and assets  
- Add CloudFront for CDN distribution  
- Add HTTPS using ACM + CloudFront  

---

## Author
Dani – Aspiring Cloud & Systems Administrator
