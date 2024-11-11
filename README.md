# 🛍️ E-Commerce Project

![e-commerce-logo](https://img.shields.io/badge/.NET-6.0-blue.svg) ![e-commerce-logo](https://img.shields.io/badge/ASP.NET%20Core-MVC-blueviolet.svg) ![e-commerce-logo](https://img.shields.io/badge/Status-In%20Progress-yellow.svg)

Dự án e-commerce xây dựng bằng C# .NET là một nền tảng mua sắm trực tuyến hiện đại, cung cấp các tính năng như quản lý sản phẩm, giỏ hàng, thanh toán và hệ thống quản lý người dùng. Mục tiêu của dự án là tạo ra một nền tảng dễ sử dụng và mở rộng cho các nhà bán lẻ.

---

## 📑 Mục Lục
- [Giới thiệu](#giới-thiệu)
- [Các Tính Năng](#các-tính-năng)
- [Cấu Trúc Dự Án](#cấu-trúc-dự-án)
- [Yêu Cầu Hệ Thống](#yêu-cầu-hệ-thống)
- [Hướng Dẫn Cài Đặt](#hướng-dẫn-cài-đặt)
- [Sử Dụng](#sử-dụng)
- [Đóng Góp](#đóng-góp)
- [Liên Hệ](#liên-hệ)

---

## 👋 Giới Thiệu
Dự án này là một ứng dụng e-commerce được phát triển với ASP.NET Core, ứng dụng các mô hình MVC và RESTful API. Người dùng có thể tìm kiếm sản phẩm, thêm vào giỏ hàng, và thực hiện thanh toán an toàn. Dự án cũng bao gồm một hệ thống quản lý người dùng dành cho admin, giúp quản lý sản phẩm và đơn hàng một cách hiệu quả.

---

## ✨ Các Tính Năng
### 🎉 Người dùng:
- Đăng ký, đăng nhập và quản lý tài khoản cá nhân.
- Tìm kiếm và duyệt sản phẩm.
- Thêm sản phẩm vào giỏ hàng và kiểm tra đơn hàng trước khi thanh toán.
- Nhận thông báo về trạng thái đơn hàng và theo dõi đơn hàng.

### 👨‍💼 Admin:
- Quản lý sản phẩm (tạo, cập nhật, xóa) và phân loại theo danh mục.
- Quản lý đơn hàng, theo dõi tiến độ và trạng thái của các đơn hàng.
- Quản lý danh sách người dùng.
- Xem báo cáo thống kê về doanh thu và hoạt động mua hàng.

---

## 📂 Cấu Trúc Dự Án
```plaintext
EcommerceProject/
│
├── Controllers/        # Các controller cho ứng dụng (xử lý yêu cầu từ người dùng)
├── Models/             # Các mô hình dữ liệu (đại diện cho các bảng trong cơ sở dữ liệu)
├── Views/              # Các view hiển thị giao diện người dùng
├── wwwroot/            # Tệp tĩnh (CSS, JS, hình ảnh)
├── Data/               # Database context và migration files
├── Services/           # Service để xử lý business logic
├── Repositories/       # Repository pattern cho dữ liệu
└── README.md           # File README của dự án
```
## 📧 Liên Hệ
Nếu bạn có bất kỳ câu hỏi hoặc ý kiến nào về dự án, vui lòng liên hệ với tôi qua email tại [minhnhatnguyenphan1207@gmail.com](https://mail.google.com/mail).
