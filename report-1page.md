# FIT4012 - Report 1 Page

## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab

- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm

- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính

**Assets:**

- Cơ sở dữ liệu điểm sinh viên
- Tài khoản đăng nhập của giảng viên và sinh viên

**CIA mapping:**

- Sự cố A -> Availability (A)
- Sự cố B -> Integrity (I)
- Sự cố C -> Confidentiality (C)

**Phân tích sự cố B:**

- Threat: Người dùng hoặc hacker chỉnh sửa trái phép dữ liệu điểm
- Vulnerability: Hệ thống chưa có phân quyền rõ ràng hoặc thiếu kiểm soát truy cập
- Mitigation: Áp dụng phân quyền người dùng, ghi log thay đổi và sử dụng xác thực mạnh (2FA)

### 4. Kết luận ngắn

Qua bài lab, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào các tình huống thực tế trong hệ thống thông tin.
Em nhận thấy việc đảm bảo tính toàn vẹn (Integrity) của dữ liệu là rất quan trọng, đặc biệt với hệ thống lưu điểm.
Phần khó nhất là phân biệt giữa các yếu tố CIA trong từng sự cố cụ thể.
Ngoài ra, em cũng học được cách sử dụng GitHub để quản lý và nộp bài.
Trong tương lai, cần chú ý phân tích kỹ từng yếu tố threat, vulnerability và mitigation để đảm bảo hệ thống an toàn hơn.
