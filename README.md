# Đơn Xin Nghỉ Học — Agent Skill cho Google Antigravity

Skill hỗ trợ học sinh và sinh viên soạn thảo đơn xin phép nghỉ học chuẩn quy thức, trang trọng và lịch sự, tuân thủ đúng nguyên tắc xử lý thông tin cá nhân.

---

## 📌 Giới thiệu chức năng

Skill **`don-xin-nghi-hoc`** được thiết kế để:
- Tự động tạo mẫu đơn xin phép nghỉ học đúng cấu trúc hành chính chuẩn (Quốc hiệu, Tiêu ngữ, Kính gửi, Thông tin người làm đơn, Lý do, Lời cam kết, Chữ ký).
- **Tuân thủ nguyên tắc xử lý thông tin:**
  - Chỉ sử dụng các thông tin người dùng cung cấp, tuyệt đối không tự bịa họ tên, lớp hoặc trường học.
  - Hỗ trợ để trống các trường thông tin (`[...]`) nếu người dùng muốn tự điền sau.
  - Tự động hỏi thêm nếu thiếu thông tin bắt buộc mà người dùng không yêu cầu để trống.
- Sử dụng văn phong trang trọng, chuẩn mực trong môi trường giáo dục.

---

## 🎯 Trường hợp sử dụng

Bạn nên sử dụng skill này khi:
- Bị ốm, sốt, đau họng hoặc có vấn đề sức khỏe cần nghỉ học điều trị.
- Gia đình có việc riêng, việc đột xuất cần làm đơn xin phép vắng mặt.
- Cần một mẫu đơn chuẩn mực có sẵn phần xác nhận của phụ huynh và cam kết hoàn thành bài vở.
- Cần tạo nhanh đơn xin nghỉ học dạng điền sẵn hoặc dạng mẫu biểu mẫu để tự in ra điền tay.

---

## ⚙️ Hướng dẫn cài đặt vào Antigravity

Bạn có thể cài đặt skill này theo phạm vi dự án (Workspace) hoặc phạm vi toàn cục (Global):

### Cách 1: Cài đặt cho một Workspace cụ thể
Sao chép thư mục `don-xin-nghi-hoc` vào thư mục `.agents/skills/` bên trong workspace làm việc của bạn:
```text
<your-workspace>/
└── .agents/
    └── skills/
        └── don-xin-nghi-hoc/
            └── SKILL.md
```

### Cách 2: Cài đặt phạm vi toàn cục (Global)
Sao chép thư mục `don-xin-nghi-hoc` vào thư mục lưu trữ skills toàn cục của Antigravity:

- **Windows:**
  ```powershell
  C:\Users\<Tên_User>\.gemini\antigravity\skills\don-xin-nghi-hoc\SKILL.md
  ```
- **macOS / Linux:**
  ```bash
  ~/.gemini/antigravity/skills/don-xin-nghi-hoc/SKILL.md
  ```

---

## 💬 Ví dụ câu lệnh kích hoạt Skill

Sau khi cài đặt, bạn chỉ cần trò chuyện tự nhiên với trợ lý AI:

1. **Yêu cầu cơ bản (để AI hỏi bổ sung thông tin cần thiết):**
   > *"Ngày mai tôi bị sốt nên muốn xin nghỉ học. Hãy viết đơn giúp tôi."*

2. **Yêu cầu tạo mẫu có chỗ trống để tự điền:**
   > *"Viết giúp tôi mẫu đơn xin nghỉ học vì bị ốm. Tôi muốn tự điền tên, lớp và trường sau."*

3. **Yêu cầu cung cấp đầy đủ thông tin:**
   > *"Tôi tên là Nguyễn Văn A, học sinh lớp 11A2 trường THPT Lê Quý Đôn. Hãy viết giúp tôi một lá đơn xin nghỉ học vào ngày mai do bị cảm cúm gửi cô giáo chủ nhiệm."*

---

## 🔒 Bảo mật & An toàn

- Skill không yêu cầu bất kỳ API key, token hay quyền truy cập mạng bên ngoài.
- Không thu thập hay lưu trữ thông tin cá nhân của người dùng.
- Hoàn toàn độc lập, an toàn khi cài đặt và sử dụng trong mọi môi trường.

