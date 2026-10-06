# BookHaven — bản thiết kế lại
Website bán sách mô phỏng phục vụ học tập/BTL kiểm thử phần mềm.

## Luồng giao diện
Trang danh sách chỉ hiển thị **ảnh bìa + tên + tác giả + thể loại + giá**.
Khi click **Xem chi tiết**, mới hiện **tóm tắt/mô tả + đánh giá sao + nhận xét độc giả + nút thêm giỏ**.

## Chức năng
- 8 sách lấy từ DOCX người dùng cung cấp; 8 ảnh bìa được trích trực tiếp từ DOCX.
- Tìm kiếm, lọc thể loại, sắp xếp.
- Chi tiết sách.
- Đánh giá sao và gửi review sau khi đăng nhập.
- Đăng nhập/đăng xuất LocalStorage.
- Giỏ hàng và thanh toán mô phỏng.
- Responsive.

## Tài khoản demo
Email: demo@bookhaven.vn
Mật khẩu: 123456

## Chạy XAMPP
Đặt thư mục vào `C:\xampp\htdocs\BookHaven` rồi bật Apache.
Mở `http://localhost/BookHaven/`.

## GitHub Pages
Upload toàn bộ project, giữ `index.html` ở thư mục gốc và bật Pages từ branch `main`.

## Lưu ý
Tài liệu nguồn có tên, tác giả, thể loại, ảnh bìa và tóm tắt. Không có giá hoặc đánh giá độc giả. Vì vậy **giá và review trong project là dữ liệu mẫu phục vụ giao diện/kiểm thử**, có thể chỉnh tại `js/script.js`.
