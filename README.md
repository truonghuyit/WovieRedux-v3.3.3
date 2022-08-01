# WovieRedux-v3.3.3
WovieRedux-v3.3.3 là một CMS Pro, linh hoạt và thân thiện với người dùng để phát trực tuyến phim và phim truyền hình dài tập với hệ thống quản lý nội dung video tiên tiến
# Các tính năng
Wovie đi kèm với một loạt các tính năng như:
TMDb Nhập phim và chương trình.
API Onesignal để thông báo cho các thành viên đã đăng ký.
Hệ thống bình luận.
Một phần diễn đàn.
Trình quản lý quảng cáo và các vị trí quảng cáo.
Nhưng chúng tôi đã cùng nhau kết hợp và bổ sung một lượng lớn các bản sửa lỗi và tính năng có thể được tìm thấy bên dưới!
Chatbox cho các yêu cầu và trò chuyện chit chung.
Hỗ trợ PWA hoạt động trên Android và iOS cho những ứng dụng không có gốc.
Hỗ trợ SEO tốt hơn.
Nhiều tùy chỉnh hơn.
Tạo sơ đồ trang web cho Google Search Console.
Nguồn cấp RSS cho người dùng của bạn đăng ký.
Chế độ bảo trì nếu bạn cần thực hiện một số công việc bí mật.
Hỗ trợ nhúng tự động bằng Remote Stream 
# Yêu cầu
PHP 7.2+
allow_url_fopen Bật
cURL 7.19.4+
PDO Bật
GD On
mbstring On
EXIF Bật
Khả năng Chmod 777 thư mục
Nếu bạn không thể Chmod 777 vì lý do máy chủ, hãy tắt chatbox
Cơ sở dữ liệu MySQL
Kiến thức cơ bản về thực thi SQL để nâng cấp
Khóa API OneSignal để hỗ trợ OneSignal
Khóa API TMDb để nhập phim và chương trình
* Tùy chọn * Cron Jobs cho sơ đồ trang web và Nguồn cấp RSS
#Trang Demo
https://watcha.movie/
# Hướng dẫn cài đặt 
Tải xuống phiên bản mới nhất
Tạo cơ sở dữ liệu trong tài khoản lưu trữ của bạn, đảm bảo rằng người dùng có các đặc quyền thích hợp '
Giải nén gói và tải tất cả các tệp lên máy chủ của bạn, đảm bảo rằng tất cả các tệp đã được tải lên
Đảm bảo chmd / quyền đối với tất cả các tệp và thư mục là chính xác (thông thường các thư mục được đặt thành 775 và các tệp được đặt thành 664 là ổn)
Các tệp và thư mục sau phải có thể ghi được (775 hoặc 777)
/index.php
/app/config/db.config.php
/app/config/config.php
/app/chatlogs/ (phải được đặt thành 777 để chatbox hoạt động)
/install/
/public/upload/
Nếu bạn gặp lỗi 500 khi cố gắng cài đặt
, hãy đảm bảo rằng tất cả các tệp đã được tải lên, đặc biệt là .htaccess
và nếu bạn đã cài đặt vào một thư mục con để chỉnh sửa .htaccess
và chmd / quyền đối với tất cả các tệp và thư mục được đặt chính xác
Truy cập URL TRANG WEB CỦA BẠN / cài đặt và chạy trình cài đặt, đảm bảo rằng không có lỗi và tiếp tục cài đặt
Nhập thông tin cơ sở dữ liệu của bạn và hoàn tất cài đặt
Thành công! WovieRedux hiện đã được cài đặt và người dùng quản trị tạm thời đã được tạo
Email: admin@admin.com
Mật khẩu: admin
Đừng quên thay đổi thông tin người dùng quản trị của bạn
Xóa các thư mục cài đặt và nâng cấp khỏi máy chủ của bạn
Cài đặt hiện đã hoàn tất
