# Lab 01 Answers

## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn Xuân Quang

**MSSV:** 1871020483

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets

Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Cơ sở dữ liệu điểm sinh viên
- Asset 2: Tài khoản đăng nhập (giảng viên & sinh viên)
- Asset 3 (nếu có): Hệ thống server lưu trữ và xử lý dữ liệu

---

## 2. Mapping CIA

- Sự cố A -> Availability (A)
- Sự cố B -> Integrity (I)
- Sự cố C -> Confidentiality (C)

---

## 3. Phân tích sự cố B

- Threat: Hacker hoặc người dùng nội bộ chỉnh sửa trái phép dữ liệu
- Vulnerability:Không có kiểm soát quyền truy cập hoặc không log thay đổi dữ liệu
- Mitigation:
  Áp dụng phân quyền (role-based access control)
  Ghi log và audit thay đổi điểm
  Sử dụng xác thực mạnh (2FA)

---

## 4. Reflection

Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề B (Integrity) trước.
Vì việc thay đổi điểm ảnh hưởng trực tiếp đến tính chính xác và công bằng của hệ thống.
Nếu dữ liệu không đáng tin cậy thì toàn bộ hệ thống mất giá trị.
Sau đó mới xử lý vấn đề Availability (A) để đảm bảo truy cập ổn định.
Cuối cùng là Confidentiality (C) để bảo vệ thông tin khỏi bị lộ.

---

## 5. Bonus Flag

FIT4012{A-A-B-I-C-C}

Flag của em: Hệ thống lưu điểm là một hệ thống quan trọng vì liên quan trực tiếp đến kết quả học tập của sinh viên.
Trong ba sự cố đã xảy ra, vấn đề nghiêm trọng nhất là việc thay đổi điểm (Integrity) vì nó ảnh hưởng đến tính chính xác và công bằng.
Nếu dữ liệu bị sai lệch, hệ thống sẽ mất độ tin cậy.
Tiếp theo, cần đảm bảo hệ thống luôn hoạt động ổn định (Availability), đặc biệt vào thời điểm quan trọng như trước khi công bố điểm.
Cuối cùng, cần bảo vệ thông tin điểm số để tránh bị lộ ra ngoài (Confidentiality).
Việc áp dụng các biện pháp như phân quyền, ghi log và xác thực mạnh là cần thiết để giảm thiểu rủi ro.
