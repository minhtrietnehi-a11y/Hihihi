# MinhTriet POS

Đây là bản web POS thử nghiệm giao diện điện thoại.

## Tài khoản thử nghiệm
- Quản lý: `admin` / `123456`
- Nhân viên Đông: `dong` / `123456`

## Đưa lên GitHub Pages
1. Tải toàn bộ file trong thư mục này lên repository GitHub.
2. Vào **Settings → Pages**.
3. Chọn **Deploy from a branch**.
4. Chọn branch `main`, thư mục `/ (root)`.
5. Lưu và chờ GitHub tạo đường dẫn.

## Lưu ý quan trọng
Bản này lưu dữ liệu bằng `localStorage`, phù hợp chạy thử trên một thiết bị. Để nhiều nhân viên dùng nhiều điện thoại và quản lý thêm món thì tất cả thiết bị đều thấy ngay, cần kết nối cơ sở dữ liệu online (Firebase/Supabase) ở bước tiếp theo.

Các chức năng đã có:
- Đăng nhập quản lý/nhân viên
- Mở ca, kết ca
- Bill theo nhân viên: Đông-0001, Đông-0002...
- Tiền mặt/chuyển khoản
- Quản lý thêm/sửa/xóa món
- Tải ảnh món
- Giá VNĐ: 25.000 = 25.000 ₫
- Thông báo thêm/sửa/xóa thành công
- Nhân viên thấy món mới ngay trên cùng thiết bị
- Lịch sử đơn và xuất CSV
- Chặn thao tác kéo xuống gây reload trên giao diện web
