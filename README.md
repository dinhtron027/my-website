# Website Cá Nhân – Đinh Trọng

Dự án website cá nhân được xây dựng bằng **HTML5 chuẩn Semantic**, **CSS3 hiện đại (Box Model, Flexbox, Responsive)** và **JavaScript thuần**, phục vụ cho việc thực hành các bài tập môn Lập trình Web (Lab 1, Lab 2, Lab 3).

---

## 🚀 Tính Năng & Cấu Trúc Website

Website bao gồm 3 trang chính với thanh điều hướng đồng nhất và thiết kế hiện đại:

### 1. Trang chủ (`index.html`)
- **Cấu trúc Semantic HTML5**: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<address>`, `<time>`.
- Phần chào mừng và giới thiệu tổng quan.
- Khu vực hiển thị các dự án nổi bật dạng thẻ `.card` có bóng đổ (box-shadow) và bo góc mềm mại.
- Liên kết điều hướng đến các trang con và kho lưu trữ GitHub repo.

### 2. Trang giới thiệu (`about.html`)
- **Hình ảnh đại diện**: Sử dụng thẻ `<figure>` và `<figcaption>` chuẩn ngữ nghĩa với ảnh tròn và bóng đổ.
- **Thuật ngữ chuyên ngành**: Sử dụng danh sách định nghĩa `<dl>`, `<dt>`, `<dd>` giải thích các khái niệm Frontend, Backend, Version Control.
- **Kỹ năng chuyên môn**: Danh sách không có thứ tự `<ul>` liệt kê 5 kỹ năng chính.
- **Lộ trình học tập**: Danh sách có thứ tự `<ol>` chia thành 3 bước rõ ràng trong học kỳ.
- **Bảng môn học**: Thẻ `<table>` đầy đủ `<caption>`, `<thead>`, `<tbody>`, `<tfoot>` tính tổng số tín chỉ.
- **Thời khóa biểu học tập**: Bảng lịch học ứng dụng thuộc tính `rowspan` để gộp các buổi học và `colspan` cho dòng ghi chú.

### 3. Trang liên hệ (`contact.html`)
- **Thông tin liên hệ trực tiếp**: Email, số điện thoại (`mailto:`, `tel:`), địa chỉ và thời gian phản hồi.
- **Form liên hệ hoàn chỉnh (Lab 3)**:
  - Phân chia rõ ràng bằng 2 thẻ `<fieldset>` và `<legend>` (Thông tin cá nhân & Nội dung liên hệ).
  - Đầy đủ các loại trường: `text`, `date` (ngày sinh), `datalist` (gợi ý trường đại học), `email`, `tel`, `select`, `radio` (chọn kênh liên hệ), `textarea`, `checkbox` (đồng ý điều khoản).
  - **Validation HTML5 thuần**: `required`, `minlength`, `maxlength`, `pattern`, `title`.
  - **Chuẩn Accessibility (WCAG 2.2)**: 100% các ô nhập đều có `<label for="...">` khớp chính xác với `id` của thẻ `<input>`.
  - **Phản hồi trạng thái**: Thông báo gửi thành công và thông báo đặt lại form khi nhấn nút "Xoá và nhập lại".

---

## 🎨 Công Nghệ Sử Dụng

- **HTML5**: Ngữ nghĩa chuẩn SEO, hỗ trợ thiết bị trợ thính (Accessibility).
- **CSS3**:
  - CSS Reset (`box-sizing: border-box`, xóa margin/padding mặc định).
  - Typography: Google Font **Inter** hiện đại.
  - Phối màu thanh lịch: `#1a2e5a` (xanh navy), `#f4f7fb` (nền sáng), `#1e293b` (màu chữ tối).
  - Thiết kế thành phần: Cards, Tables, Forms, Alerts animation.
- **JavaScript**: Xử lý sự kiện gửi tin nhắn và làm mới form linh hoạt.

---

## 📂 Cấu Trúc Thư Mục

```text
my-website/
├── index.html      # Trang chủ
├── about.html      # Trang giới thiệu
├── contact.html    # Trang liên hệ & biểu mẫu
├── style.css       # File định kiểu toàn bộ giao diện
└── README.md       # Tài liệu hướng dẫn dự án
```

---

## 🛠️ Hướng Dẫn Sử Dụng

1. Clone dự án về máy tính:
   ```bash
   git clone https://github.com/dinhtron027/my-website.git
   ```
2. Mở thư mục dự án bằng **Visual Studio Code** hoặc trình soạn thảo bất kỳ.
3. Chạy trang web bằng tiện ích mở rộng **Live Server** hoặc nhấp đúp trực tiếp vào file `index.html` để mở trên trình duyệt.

---

## 👤 Tác Giả

- **Họ và tên**: Đinh Trọng
- **Email**: [cutrong236@email.com](mailto:cutrong236@email.com)
- **GitHub**: [github.com/dinhtron027](https://github.com/dinhtron027)
