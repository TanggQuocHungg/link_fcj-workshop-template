---
title: "Summary and Resources"
date: 2026-07-01
weight: 10
chapter: false
pre: " <b> 5.10. </b> "
---

After 8 weeks of research, design, and hands-on implementation, the **Ride-Booking Management System has been completed. The project successfully applies a Serverless architecture on AWS, fully meeting the criteria for High Availability, Auto-scaling, and cost optimization (Pay-as-you-go).

Below are all the resources, source code, and the actual report video of the project, so that the review committee can experience and evaluate it directly.

#### 1. Live App Experience
The Frontend has been packaged and automatically deployed (CI/CD) via **AWS Amplify**, connected directly to the Serverless API system running in the Production environment.
* **Ride-Booking Website:** [Access the Application Here](https://staging.d3i51qopjlikyk.amplifyapp.com/)

#### 2. End-to-End Demo Video
The video presents the system architecture in detail and demonstrates the core business flow: from the user's ticket-booking action, payment via the VNPAY gateway, to the Webhook (IPN) process automatically updating the DynamoDB database and triggering Amazon SES to send an invoice email.
* **Report Video:** [Watch the Demo Video on Google Drive](https://drive.google.com/drive/folders/1HpuU1ASlhDOr3I_ceohtRaS_K4Xx3qWU?usp=drive_link)

#### 3. Source Code
The entire project source code is well-organized and publicly hosted. It includes the Frontend interface source code (ReactJS), the Backend logic-handling functions (Node.js/AWS Lambda), and the API Gateway configurations.
* **GitHub Repository:** [Access the Project Source Code](https://github.com/TanggQuocHungg/Project_ThucTap_BusBooking.git)
