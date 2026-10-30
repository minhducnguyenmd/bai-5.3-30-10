# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Khánh Đức
- **Mã số sinh viên:** 24810320072
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI BÀI TẬP 5.3: HỆ THỐNG QUẢN LÝ QUÁN CAFE & BÁN HÀNG (POS
CAFE SYSTEM)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="1434" height="896" alt="Screenshot 2026-10-30 082425" src="https://github.com/user-attachments/assets/2aff62c2-404c-48a0-8e1d-02c614c809e7" />

- Giao diện khi chọn bàn và gọi món
<img width="1429" height="894" alt="Screenshot 2026-10-30 082455" src="https://github.com/user-attachments/assets/fb76e27d-e718-41c3-9a4f-7ad2721367e2" />

- Giao diện xác nhận thanh toán tổng số tiền
<img width="1434" height="892" alt="Screenshot 2026-10-30 082514" src="https://github.com/user-attachments/assets/be762ed5-3a5e-4028-8173-729cb7fb5112" />

- Giao diện khi thanh toán xong, bàn có khách trở thành bàn trống
<img width="1436" height="901" alt="Screenshot 2026-10-30 082525" src="https://github.com/user-attachments/assets/c802eb4c-6570-454e-86f2-e8ba5de5db54" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `CafePOSDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `DBConnect.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
