# Quản Lý Phòng Trọ Sinh Viên

Quản lý phòng trọ sinh viên bằng ngôn ngữ C#. Dưới đây là đề cương chi tiết cho từng thành viên, mô tả chức năng modules và layout draft cho các chức năng cần quản lý trong hệ thống (quản lý thông tin phòng, quản lý thông tin sinh viên, đăng nhập, đăng ký và báo cáo).

## Thành viên 1: Quản lý Thông Tin Phòng

**Nhiệm vụ:**
- Quản lý danh sách các phòng (thêm, sửa, xóa phòng).
- Theo dõi trạng thái phòng (còn trống, đã thuê).

**Chức năng Modules:**
1. **Danh sách phòng:**
   - Xem danh sách phòng hiện có (hiển thị số phòng, loại phòng, sức chứa, trạng thái).
   - Tìm kiếm phòng theo loại hoặc trạng thái.

2. **Thêm/Sửa/Xóa phòng:**
   - **Thêm phòng:** Ghi nhận thông tin phòng (số phòng, loại phòng, sức chứa, trạng thái ban đầu).
   - **Sửa phòng:** Cho phép chỉnh sửa thông tin phòng (loại phòng, trạng thái).
   - **Xóa phòng:** Xóa phòng không còn sử dụng.

**Layout Draft:**
- **Trang Quản Lý Phòng:**
  - Hiển thị bảng danh sách các phòng (các cột: Số phòng, Loại phòng, Sức chứa, Trạng thái).
  - Nút chức năng: [Thêm phòng], [Sửa phòng], [Xóa phòng].
  - Form thêm/sửa phòng: Nhập số phòng, loại phòng, sức chứa, trạng thái.

---

## Thành viên 2: Quản lý Thông Tin Sinh Viên

**Nhiệm vụ:**
- Quản lý thông tin sinh viên thuê trọ (thêm, sửa, xóa).
- Ghi nhận sinh viên đang thuê phòng và liên kết với thông tin phòng.

**Chức năng Modules:**
1. **Danh sách sinh viên:**
   - Xem danh sách sinh viên đang thuê trọ (hiển thị tên, mã số, lớp, số phòng đang ở).
   - Tìm kiếm sinh viên theo tên hoặc phòng.

2. **Thêm/Sửa/Xóa sinh viên:**
   - **Thêm sinh viên:** Ghi nhận thông tin (tên, mã số sinh viên, ngày sinh, số phòng).
   - **Sửa sinh viên:** Chỉnh sửa thông tin sinh viên khi cần (phòng mới, thông tin cá nhân).
   - **Xóa sinh viên:** Xóa sinh viên đã rời khỏi trọ.

**Layout Draft:**
- **Trang Quản Lý Sinh Viên:**
  - Hiển thị bảng danh sách sinh viên (các cột: Tên, Mã số, Ngày sinh, Số phòng).
  - Nút chức năng: [Thêm sinh viên], [Sửa sinh viên], [Xóa sinh viên].
  - Form thêm/sửa sinh viên: Nhập tên, mã số, ngày sinh, số phòng.

---

## Thành viên 3: Đăng Nhập, Đăng Ký, và Báo Cáo

**Nhiệm vụ:**
- Xây dựng trang đăng nhập và đăng ký cho người dùng.
- Quản lý quyền truy cập hệ thống (admin, user).
- Tạo báo cáo thống kê phòng trọ và sinh viên.

**Chức năng Modules:**
1. **Đăng nhập/Đăng ký:**
   - **Đăng nhập:** Xác thực tài khoản người dùng (admin/user).
   - **Đăng ký:** Cho phép thêm tài khoản mới.
   - **Quản lý phiên làm việc:** Duy trì trạng thái đăng nhập.

2. **Báo cáo:**
   - Báo cáo danh sách phòng trọ (phòng trống, phòng đã thuê).
   - Báo cáo sinh viên (số lượng sinh viên theo phòng, số lượng tổng thể).

**Layout Draft:**
- **Trang Đăng Nhập:**
  - Form đăng nhập: Nhập tên đăng nhập, mật khẩu.
  - Nút chức năng: [Đăng nhập], [Quên mật khẩu].
  
- **Trang Đăng Ký:**
  - Form đăng ký tài khoản: Nhập tên, email, mật khẩu, phân quyền.
  - Nút chức năng: [Đăng ký].
  
- **Trang Báo Cáo:**
  - Hiển thị báo cáo dạng bảng và biểu đồ:
    - Số phòng trống/đã thuê.
    - Số sinh viên đang thuê trọ.

---

## Tổng hợp công việc:

| Thành viên  | Chức năng chính               | Layout Draft                      |
|-------------|-------------------------------|------------------------------------|
| Thành viên 1| Quản lý Thông Tin Phòng       | Trang Quản Lý Phòng               |
| Thành viên 2| Quản lý Thông Tin Sinh Viên   | Trang Quản Lý Sinh Viên           |
| Thành viên 3| Đăng Nhập, Đăng Ký, và Báo Cáo| Trang Đăng Nhập, Trang Đăng Ký, Trang Báo Cáo |


