# Thư viện Trường THPT Thốt Nốt

Bản đóng gói cập nhật ngày 06/10/2026, dùng trực tiếp trên GitHub Pages.
Giữ nguyên danh mục sách, tìm kiếm, bộ lọc, hình ảnh, banner và footer địa chỉ. Mục lượt truy cập đã được ẩn; bản này không gọi dịch vụ thống kê truy cập.

## Đưa website lên GitHub Pages

1. Giải nén file ZIP trên máy tính.
2. Đăng nhập https://github.com và tạo kho (repository) mới, ví dụ `thu-vien-thot-not`, chọn **Public**. Có thể chọn tạo README khi tạo kho.
3. Mở kho, chọn **Add file → Upload files**. Tải toàn bộ nội dung thư mục đã giải nén lên, bao gồm thư mục `fonts`. Không tải nguyên file ZIP và không đặt tất cả vào một thư mục con.
4. Đảm bảo `index.html`, `catalog.json`, `app.js`, các file CSS và các ảnh nằm ngay ở thư mục gốc của kho. Chọn **Commit changes**. Nếu đã có README mẫu, thay bằng README trong gói này hoặc bỏ qua file README khi tải lên.
5. Mở **Settings → Pages**. Trong **Build and deployment**, chọn **Source: Deploy from a branch**.
6. Chọn **Branch: main**, thư mục **/(root)**, rồi nhấn **Save**.
7. Chờ GitHub triển khai; quay lại **Settings → Pages** để lấy địa chỉ website.

Địa chỉ thường có dạng `https://TEN_TAI_KHOAN.github.io/thu-vien-thot-not/`.
Nếu muốn đường dẫn gốc ngắn hơn, đặt tên kho là `TEN_TAI_KHOAN.github.io`; địa chỉ sẽ là `https://TEN_TAI_KHOAN.github.io/`.

Không cần cài Node.js hay chạy lệnh build. Khi kiểm tra trên máy, không mở `index.html` bằng cách nhấp đúp vì trình duyệt có thể chặn tải danh mục JSON; hãy kiểm tra sau khi đăng lên Pages hoặc dùng máy chủ HTTP cục bộ.

## Cập nhật lần sau

Thay file tương ứng trong kho và commit để GitHub Pages tự triển khai lại. Nếu trang chưa hiện thay đổi, nhấn Ctrl+F5.

Hướng dẫn GitHub chính thức:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
