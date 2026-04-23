# 🚀 QuanLyTuyenDung

### Recruitment Management System

<p align="center">
  <i>Hệ thống quản lý tuyển dụng toàn diện xây dựng trên nền tảng .NET</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/.NET-6-blue" />
  <img src="https://img.shields.io/badge/SQL-Server-red" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 📖 Giới thiệu

**QuanLyTuyenDung** là giải pháp quản trị quy trình tuyển dụng, giúp tối ưu hóa việc kết nối giữa doanh nghiệp và ứng viên:

* 📢 Đăng tin tuyển dụng
* 📄 Quản lý hồ sơ ứng viên
* 🔔 Theo dõi và phản hồi kết quả

---

## 📚 Mục lục

* [✨ Tính năng chính](#-tính-năng-chính)
* [🛠️ Công nghệ sử dụng](#️-công-nghệ-sử-dụng)
* [🧠 Kiến trúc hệ thống](#-kiến-trúc-hệ-thống)
* [📁 Cấu trúc thư mục](#-cấu-trúc-thư-mục)
* [⚙️ Hướng dẫn cài đặt](#️-hướng-dẫn-cài-đặt)
* [🚀 Lộ trình phát triển](#-lộ-trình-phát-triển)

---

## ✨ Tính năng chính

### 🔐 Quản trị hệ thống (Admin)

* 📊 Dashboard: Thống kê tổng quan tuyển dụng
* 📢 Quản lý tin tuyển dụng (CRUD)
* 📋 Quản lý ứng viên & trạng thái hồ sơ
* 🛡️ Phân quyền người dùng (Role-based Authorization)

### 🧑‍💼 Dành cho Ứng viên (User)

* 🔍 Tìm kiếm việc làm theo tiêu chí
* 📄 Nộp hồ sơ trực tuyến nhanh chóng
* 🔔 Nhận thông báo trạng thái hồ sơ

---

## 🛠️ Công nghệ sử dụng

| Thành phần | Công nghệ                        |
| ---------- | -------------------------------- |
| Backend    | ASP.NET Core (MVC)               |
| ORM        | Entity Framework Core            |
| Database   | SQL Server                       |
| UI/UX      | Bootstrap 5, Razor Views, jQuery |
| Security   | ASP.NET Core Identity            |

---

## 🧠 Kiến trúc hệ thống

Dự án được thiết kế theo mô hình **MVC + DAO**, giúp tách biệt rõ ràng các tầng:

* **Models** → Định nghĩa dữ liệu (Entities)
* **Views** → Giao diện người dùng (Razor)
* **Controllers** → Xử lý logic nghiệp vụ
* **DAO / Repository** → Truy cập cơ sở dữ liệu

👉 Ưu điểm:

* Dễ bảo trì
* Dễ mở rộng
* Tách biệt rõ trách nhiệm

---

## 📁 Cấu trúc thư mục

```bash id="7c5jfx"
QuanLyTuyenDung/
│
├── Controllers/       # Xử lý logic & routing
├── Models/            # Entities
├── DAO/               # Data access layer
├── Views/             # Razor (.cshtml)
├── wwwroot/           # CSS, JS, Images
├── database/
│   └── tuyendung.sql  # Script DB
├── appsettings.json   # Config hệ thống
└── Program.cs         # Entry point
```

---

## ⚙️ Hướng dẫn cài đặt

### 🔹 1. Yêu cầu hệ thống

* .NET SDK 6.0+
* SQL Server / LocalDB
* Visual Studio 2022

---
    
### 🔹 2. Clone project

```bash id="1mrj5p"
git clone https://github.com/hoanghieuinfo/QuanLyTuyenDung.git
```

---

### 🔹 3. Thiết lập Database

* Mở **SQL Server Management Studio (SSMS)**
* Chạy file:

```bash id="pxc4dn"
database/tuyendung.sql
```

---

### 🔹 4. Cấu hình kết nối

Trong `appsettings.json`:

```json id="6o3jlt"
"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=QLTuyenDung;Trusted_Connection=True;TrustServerCertificate=True"
}
```

---

### 🔹 5. Chạy ứng dụng

* Mở file `.sln` bằng Visual Studio
* Nhấn **F5** hoặc **Start**

---

## 🚀 Lộ trình phát triển

* [ ] 📄 Upload & quản lý CV
* [ ] 📧 Gửi email tự động
* [ ] 📊 Xuất báo cáo (Excel/PDF)
* [ ] ☁️ Deploy Docker / Azure

---

## 👨‍💻 Tác giả

**HoangHieuInfo**

> Học tập & phát triển 🚀

---

## ⭐ Hỗ trợ

Nếu bạn thấy dự án hữu ích:
👉 Hãy **Star ⭐ repo** để ủng hộ!

---
