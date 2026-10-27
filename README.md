# Hệ Thống Ôn Tập Điểm 10 Tin Học 12 - Kết Nối Tri Thức (Trọn Bộ 28 Bài)

Hệ thống ôn luyện trắc nghiệm trực quan Tin Học 12 (Kết Nối Tri Thức Với Cuộc Sống) gồm 28 bài trọng tâm, 7 chủ đề với 3.080 câu hỏi phân loại chi tiết. Dự án đã được đóng gói hoàn chỉnh, chuẩn hóa để triển khai trực tiếp lên **Vercel**.

---

## 🔒 Cam kết tính toàn vẹn dữ liệu gốc

File HTML gốc được giữ nguyên bản tuyệt đối 100%, **không thay đổi bất kỳ ký tự nào**:
- **SHA256 file gốc**: `319C2E8E41E101D26E630A469FAEBD9C4F7478646F788B11C193B91E372EBDED`
- **SHA256 `index.html`**: `319C2E8E41E101D26E630A469FAEBD9C4F7478646F788B11C193B91E372EBDED`
- Trạng thái: **Khớp 100% (Byte-for-byte)**.

---

## 📁 Cấu trúc thư mục

```text
tin-hoc-12-vercel/
├── index.html         # File giao diện & dữ liệu hoàn chỉnh (giữ nguyên gốc)
├── vercel.json        # Cấu hình định tuyến, security headers cho Vercel
├── package.json       # Khai báo metadata và script chạy thử nghiệm
├── .gitignore         # Bỏ qua thư mục tạm, cache khi đưa lên Git
└── README.md          # Hướng dẫn chi tiết triển khai Vercel
```

---

## 🚀 Hướng dẫn triển khai lên Vercel

### Cách 1: Triển khai qua GitHub (Khuyên dùng - Đơn giản & Tự động nhất)

1. Tạo một repository mới trên [GitHub](https://github.com/new) (ví dụ: `tin-hoc-12-kntt`).
2. Mở terminal tại thư mục này và đẩy code lên:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for Vercel deployment"
   git branch -M main
   git remote add origin https://github.com/<tai-khoan-cua-ban>/tin-hoc-12-kntt.git
   git push -u origin main
   ```
3. Truy cập [vercel.com](https://vercel.com/) và đăng nhập.
4. Bấm **"Add New..."** → **"Project"**.
5. Chọn kho GitHub bạn vừa tạo, bấm **"Import"**.
6. Giữ nguyên cấu hình mặc định (Framework Preset: *Other*) và bấm **"Deploy"**.
7. Sau 10 - 20 giây, website của bạn sẽ hoạt động tại địa chỉ: `https://<ten-du-an>.vercel.app`.

---

### Cách 2: Triển khai trực tiếp bằng Vercel CLI

Nếu bạn đã cài đặt Node.js và Vercel CLI:

1. Mở PowerShell hoặc Terminal tại thư mục này:
   ```powershell
   cd C:\Users\hp\.gemini\antigravity\scratch\tin-hoc-12-vercel
   ```
2. Chạy lệnh:
   ```bash
   npx vercel
   ```
3. Đăng nhập theo hướng dẫn trên màn hình và xác nhận các câu hỏi mặc định (nhấn Enter liên tục).
4. Để xuất bản lên domain chính thức (Production):
   ```bash
   npx vercel --prod
   ```

---

## 💻 Kiểm tra trên máy cục bộ (Local Preview)

Nếu muốn mở xem thử trên máy tính trước khi đẩy lên Vercel:
- **Cách đơn giản nhất:** Nhấp đúp trực tiếp vào file `index.html` để mở trong trình duyệt Chrome/Edge.
- **Hoặc chạy web server mini:**
  ```bash
  npm start
  ```
  Truy cập: `http://localhost:3000`.
