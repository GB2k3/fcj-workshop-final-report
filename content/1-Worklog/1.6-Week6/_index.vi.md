---
title: "Worklog Tuần 6"
date: 2026-04-13
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu Tuần 6:

* Tiếp tục phát triển hệ thống đăng ký ứng dụng  
* Áp dụng Terraform để triển khai hạ tầng AWS  
* Tích hợp dịch vụ xác thực vào hệ thống  

### Các công việc thực hiện trong tuần:
| Ngày | Công việc                                                                                                      | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| ---- | -------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------ |
| 2    | - Tiếp tục triển khai chức năng đăng ký ứng dụng <br> - Cải thiện logic backend                               | 13/04/2026   | 13/04/2026      |                    |
| 5    | - Nghiên cứu và triển khai Cognito để xác thực người dùng <br> - Tích hợp Cognito User Pool vào hệ thống      | 16/04/2026   | 16/04/2026      |                    |

### Kết quả đạt được trong Tuần 6:

* Sử dụng thành công Terraform để triển khai và quản lý các dịch vụ AWS cần thiết cho hệ thống đăng ký ứng dụng.

* Xây dựng và đẩy Docker image lên Amazon ECR, sau đó triển khai ứng dụng bằng Amazon ECS.

* Tích hợp Amazon Cognito vào hệ thống để xác thực người dùng và quản lý user pool.

* Cập nhật logic backend để hoạt động tương thích với luồng xác thực của Cognito và đảm bảo hệ thống vận hành đúng sau khi tích hợp.

* Hiểu rõ hơn về cách các dịch vụ AWS (ECS, ECR, Cognito, Terraform) tương tác với nhau trong môi trường dự án thực tế.
