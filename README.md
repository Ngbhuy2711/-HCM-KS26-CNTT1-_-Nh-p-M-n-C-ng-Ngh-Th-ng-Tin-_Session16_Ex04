# ***Phần 1: So sánh & Đánh giá***
 ##  Lập bảng so sánh Ưu/Nhược điểm của Incognito Mode vs Dedicated Profile.
 | Tiêu Chí | incognito mode | dedicated profile |
 | :--- | :---: | ---: |
 | Ưu điểm | phù hợp để kiểm tra nhanh trạng thái đăng nhập | - duy trì trạng thái làm việc lâu dài |
 |          | | - Quản lý bookmark và extension riêng biệt cho từng mục đích |
 | Nhược điểm | -tốn thời gian setup lại môi trường hàng ngày | Tốn thêm dung lượng ổ đĩa nhỏ cho từng profile |
 |             |  - Mất sạch bookmark tài liệu kỹ thuật |

# ***Phần 2: Lựa chọn***

## Tư vấn cho thành viên A mô hình 3 Profile chuẩn Dev (**Personal - Work - Sandbox**) và lập luận tại sao đây là giải pháp tối ưu hơn Ẩn danh.
1. Profile 1 ( personal ) :

   -Mục đích : sử dụng cho nhu cầu giải trí,tin tức,tài khoản cá nhân

   -Đặc điểm : đảm bảo tính riêng tư
2. Profile 2 ( dự án LMS ) :

   -Mục đích : tài khoản gmail công ty , github dự án lms

   -Tài nguyên lưu trữ : lưu trữ toàn bộ bookmark tài liệu kỹ thuật

   -Extensions : react devtools

 3. Profile 3 ( sandbox ) :

    -Mục đích: Chuyên dùng để test vai trò người dùng khác nhau

    -Đặc điểm: tích hợp extension autofill lưu danh sách tài khoản test

 ### lập luận tại sao đây là giải pháp tối ưu hơn Ẩn danh.
   - Giải quyết triệt để khi mất bookmark : mọi dự án file điều sẽ được lưu cố định tại bookmark tại `profile work` . Dù có tắt máy hay khởi động lại , chỉ cần mở profile là được khôi phục nguyên vẹn
   - tối ưu hóa thời gian : thay vì mỗi sáng phải gõ lại tài khoản ở chế độ ẩn danh , profile sandbox lưu sẵn phiên đăng nhập
   - hỗ trợ công cụ dev toàn diện : các công cụ hỗ trợ phát hoạt động ổn định và lưu cấu hình dài trên đeicated profile mà không bị hạn chế quyền như ở incognito mode
   - Tránh nhầm lẫn ngữ cảnh : gán màu sắc giao diện và avatar riêng cho từng profile giúp dev phân biệt dễ dàng
