---
title: "Tổng kết và Tài nguyên"
date: 2026-07-22
weight: 10
chapter: false
draft: false
pre: " <b> 5.10. </b> "
---

Sau 8 tuần nghiên cứu, thiết kế và triển khai thực tế, hệ thống **Quản lý Đặt vé xe (Bé Đặt Xe)** đã được hoàn thiện. Dự án áp dụng thành công kiến trúc Serverless trên AWS, đáp ứng đầy đủ các tiêu chí về tính khả dụng cao (High Availability), khả năng mở rộng tự động (Auto-scaling) và tối ưu chi phí (Pay-as-you-go).

Dưới đây là toàn bộ tài nguyên, mã nguồn và video báo cáo thực tế của dự án để hội đồng có thể trải nghiệm và đánh giá trực tiếp.

#### 1. Trải nghiệm Hệ thống Thực tế (Live App)
Hệ thống Frontend đã được đóng gói và triển khai tự động (CI/CD) thông qua **AWS Amplify**, kết nối trực tiếp với hệ thống API Serverless đang chạy ở môi trường Production.
* **Website Đặt xe:** [Truy cập Ứng dụng tại đây](https://staging.d3i51qopjlikyk.amplifyapp.com/) 

#### 2. Video Demo Toàn trình (End-to-End Workflow)
Video trình bày chi tiết kiến trúc hệ thống và demo luồng nghiệp vụ cốt lõi: Từ thao tác đặt vé của người dùng, thanh toán qua cổng VNPAY, cho đến quá trình Webhook (IPN) tự động cập nhật cơ sở dữ liệu DynamoDB và kích hoạt Amazon SES gửi email hóa đơn.
* **Video Báo cáo:** [Xem Video Demo trên Google Drive](https://drive.google.com/drive/folders/1HpuU1ASlhDOr3I_ceohtRaS_K4Xx3qWU?usp=drive_link) 

#### 3. Mã nguồn Hệ thống (Source Code)
Toàn bộ mã nguồn của dự án được tổ chức chặt chẽ và lưu trữ công khai. Bao gồm mã nguồn giao diện (ReactJS), các hàm xử lý logic Backend (Node.js/AWS Lambda), và các cấu hình API Gateway.
*  **GitHub Repository:** [Truy cập Mã nguồn dự án](https://github.com/TanggQuocHungg/Project_ThucTap_BusBooking.git) 
