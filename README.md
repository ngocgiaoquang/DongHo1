# DongHo
DongHo là trang web quản lý cửa hàng đồng hồ được viết bằng php( bao gồm có các chức năng thêm, xóa, sửa, đăng nhập Admin)
## Yêu cầu
- Cần có XAMPP
- Cần có công cụ IDE: VsCode
## Cài đặt
- Tải [XAMPP](https://www.apachefriends.org/download.html) về máy.
- Cài đặt XAMPP trên máy.
- Bật Apache và MySQL.
- Đặt cổng mặc định cho XAMPP( Apache:8899, MySQL:3306)
- Nhấn vào "Config" ngay hàng Apache chọn "Apache(httpd.conf)" kéo xuống kiếm dòng "Listen 80" đổi thành "Listen 8899" và lưu.
- Cho thư mục "a" chứa folder source VsCode đã được giải nén từ file zip vào "xampp/htdocs".
- Vào trang web nhập trên thanh URL "localhost:8899" truy cập vào PHPMyAdmin, tạo database tên "qldh" và nhập file "qldh.sql" từ thư mục "a".
- Vào trang web nhập trên thanh URL "localhost:8899/a" đăng nhập (Tên đăng nhập: admin ; Mật khẩu: 1234 ) và chạy trang quản lý.
