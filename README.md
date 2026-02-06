# Task Management
## Mô tả
Hệ thống Quản lý công việc (Trello Clone) là nền tảng cộng tác dựa trên mô hình Kanban, cho phép quản lý dự án trực quan qua các bảng công việc và cột trạng thái linh hoạt. Người dùng có thể tạo nhiệm vụ, gán thành viên, đặt hạn chót và tương tác qua bình luận, đồng thời theo dõi tiến độ tổng thể bằng các công cụ thống kê. Hệ thống phân quyền chặt chẽ cho Admin, Quản lý dự án và Thành viên, giúp tối ưu hóa quy trình làm việc và đảm bảo tính minh bạch cho nhóm.
## Thành viên nhóm
| MSSV | Họ tên | Vai trò |
|------|--------|---------|
| 2351010180 | Phạm Anh Quyền | Trưởng nhóm |
| 2351010025 | Nguyễn Hữu Công | Thành Viên |
| 2351010022 | Huỳnh Thế Cảnh | Thành Viên |
## Công nghệ sử dụng
- Backend: Java + Spring boot
- Frontend: React
- Database: MySQL
- Message Queue: RabbitMQ
- Container: Docker + Docker Compose
## Kiến trúc
![Architecture](docs/architecture/c4-container.png)
## Cài đặt và chạy
### Yêu cầu
- Docker Desktop
- Git
### Chạy với Docker Compose
- git clone https://github.com/quyendzvcb/Taskify.git

- cd Taskify

- docker-compose up -d
### Truy cập
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000
- RabbitMQ Management: http://localhost:15672
## Demo
[Link video demo hoặc screenshots]
## Tài liệu
- [ADRs](docs/adrs/)
- [API Documentation](docs/api/)
