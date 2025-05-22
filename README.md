# AES File Encryptor Web App

Ứng dụng web mã hóa/giải mã file sử dụng thuật toán AES (CBC) với giao diện hiện đại lấy cảm hứng từ Instagram.

## 🚀 Tính năng
- Mã hóa và giải mã file (ảnh, tài liệu, v.v) bằng AES-256 (CBC)
- Giao diện đẹp, hiện đại, thân thiện người dùng
- Hỗ trợ upload file lên tới 16MB
- Mọi thao tác xử lý đều thực hiện trên máy chủ, đảm bảo bảo mật

## 🖥️ Demo giao diện
![Screenshot](screenshot.png)

## 🛠️ Công nghệ sử dụng
- Python 3
- Flask
- PyCryptodome (AES)
- HTML5, CSS3 (Glassmorphism, Gradient, Responsive)
- Bootstrap 5, Animate.css

## ⚡ Hướng dẫn cài đặt & chạy
1. **Clone repo:**
   ```bash
   git clone <repo-url>
   cd <tên-thư-mục-repo>
   ```
2. **Cài đặt thư viện:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Chạy ứng dụng:**
   ```bash
   python app.py
   ```
4. **Truy cập:**
   Mở trình duyệt và vào địa chỉ: [http://localhost:5000](http://localhost:5000)

## 📝 Hướng dẫn sử dụng
1. Chọn file muốn mã hóa hoặc giải mã (hỗ trợ nhiều định dạng)
2. Nhập khóa bí mật (có thể là bất kỳ chuỗi nào, càng dài càng an toàn)
3. Chọn thao tác: Mã hóa hoặc Giải mã
4. Nhấn **Thực hiện** và tải về file kết quả

> **Lưu ý:**
> - Khóa phải giống nhau khi mã hóa và giải mã.
> - Nếu giải mã sai khóa, file kết quả có thể bị lỗi.

## 📂 Cấu trúc thư mục
```
├── app.py              # Flask backend
├── requirements.txt    # Thư viện Python
├── templates/
│   └── index.html      # Giao diện web
```

## 📜 Bản quyền & Giấy phép
- Sử dụng tự do cho mục đích học tập, nghiên cứu.
- Không chịu trách nhiệm về việc mất mát dữ liệu do sử dụng sai mục đích.

---
**Tác giả:** NGUYỄN HỮU TUẤN MINH  
**Liên hệ:** Gamincoder@gmail.com
