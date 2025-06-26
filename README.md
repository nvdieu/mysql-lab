# 🐬 MySQL + Workbench bằng Docker

## 📌 Giới thiệu

Môi trường này giúp nhanh chóng cài đặt và làm việc với **MySQL** thông qua:
- Ứng dụng đồ họa chuyên nghiệp: **MySQL Workbench**

Phù hợp để học SQL trên cả **Mac** và **Windows**.
---
### b0: Tạo thư mục làm việc: vd mysql-lab
    Dặt file **docker-compose.yal** tại thư mục này
### b1: Cài đặt MySQL Workbench
[https://www.mysql.com/products/workbench/](https://www.mysql.com/products/workbench/)

### b2: Cài đặt Docker Desktop
Tải Docker Desktop tại đây:

[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

### b3: Khởi chạy dịch vụ
Mở terminal (hoặc PowerShell), chạy lệnh:

    docker compose up -d

### b4: Chạy MySQL Workbench
Tại MySQL Connecttion: 
Nhấn dấu + dể tạo một connection mới nếu là chạy lần đầu.

Thiết lập:
    
    Connection Name: MySQL Docker (hoặc tên gì cũng được vd: CSDL)
    
    Hostname: localhost

    Port: 3306

    Username: student (hoặc root nếu dùng tài khoản admin)

    Password: student123 (hoặc rootpass nếu dùng root)

    Default Schema: demo_db (có thể để trống cũng được)

### Kết thúc
Thoát khỏi Workbench
Từ cửa sổ lệnh: 

    docker compose down
