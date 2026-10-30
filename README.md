# Bài tập: Phân quyền chia sẻ dữ liệu an toàn

## Phần 1. Phân tích

An vi phạm **Quy tắc Cờ Đỏ Bảo mật** vì:

1. Chọn **Anyone with the link**: bất kỳ ai có liên kết đều có thể truy cập.
2. Cấp quyền **Editor**: người có liên kết có thể sửa hoặc xóa dữ liệu.
3. Tài liệu chứa **SĐT khách hàng**: làm lộ thông tin cá nhân và gây mất dữ liệu khi liên kết bị phát tán.

### Phân biệt 3 mức quyền

| Quyền | Khả năng |
|---|---|
| **Viewer** | Chỉ xem. |
| **Commenter** | Xem và bình luận, không sửa nội dung. |
| **Editor** | Xem, sửa và xóa nội dung. |

## Phần 2. Sửa lỗi

**(1) Cấp quyền nào cho cộng tác viên?**

- **Commenter** nếu chỉ cần góp ý.
- **Editor** nếu thực sự cần chỉnh sửa, nhưng chỉ cấp cho **email cụ thể** và chỉ trên tài liệu cần thiết.

**(2) Chế độ chia sẻ nào an toàn?**

- Chọn **Restricted (Bị hạn chế)** và chỉ thêm đúng email người được phép.
- **Không có chế độ nào an toàn 100%**; người được cấp quyền vẫn có thể làm lộ thông tin. Nên hạn chế hoặc ẩn SĐT khách hàng khi không cần thiết.

**(3) Bật tính năng gì để ngăn mời thêm người lạ?**

- Trong **Share → Settings (biểu tượng bánh răng)**, **tắt** tùy chọn **“Editors can change permissions and share”** (Cho phép người chỉnh sửa thay đổi quyền và chia sẻ).
- Chủ sở hữu định kỳ kiểm tra danh sách người có quyền truy cập.

## Kết luận

**Chỉ chia sẻ cho đúng người, cấp đúng quyền cần dùng và không công khai dữ liệu khách hàng.**
