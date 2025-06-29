# 🐬 MySQL + Workbench bằng Docker

## 📌 Giới thiệu

Môi trường này giúp nhanh chóng cài đặt và làm việc với **MySQL** thông qua:
- Ứng dụng đồ họa chuyên nghiệp: **MySQL Workbench**

Phù hợp để học SQL trên cả **Mac** và **Windows**.
---
### b1: Cài đặt MySQL Workbench
[https://www.mysql.com/products/workbench/](https://www.mysql.com/products/workbench/)

### b2: Cài đặt Docker Desktop
Tải Docker Desktop tại đây:

[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

```bash
git clone https://github.com/nvdieu/mysql-lab.git
cd mysql-lab
docker compose up -d
```

### b3: Nếu tải về thì giải nén hoặc clone:
Mở terminal (hoặc PowerShell):

git clone https://github.com/nvdieu/mysql-lab.git
cd mysql-lab
docker compose up -d

### b4: Chạy MySQL Workbench
Tại MySQL Connecttion: 
Nhấn dấu + dể tạo một connection mới nếu là chạy lần đầu.

Thiết lập:
    
    Connection Name: MySQL Docker (hoặc tên gì cũng được vd: CSDL)
    
    Hostname: localhost

    Port: 3306

    Username: root

    Password: 1234

    Default Schema: demo_db (có thể để trống cũng được)

### Kết thúc
Thoát khỏi Workbench
Từ cửa sổ lệnh: 

    docker compose down
