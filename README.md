1. Tổng Quan
Báo cáo cung cấp thông tin về quá trình kiểm thử sử dụng Postman để đánh giá tính năng và hiệu suất của một ứng dụng. Chúng tôi sẽ trình bày về môi trường kiểm thử, các bước kiểm thử, kết quả và các phát hiện chính.

2. Môi Trường Kiểm Thử
Công cụ Kiểm Thử: Postman
Mục Tiêu Kiểm Thử: Đánh giá tính năng và hiệu suất của API.

4. Các Bước Kiểm Thử
Bước 1: Xác thực Người Dùng

Mô tả: Kiểm tra tính năng xác thực người dùng bằng cách gửi yêu cầu POST đến API với thông tin đăng nhập.
Số Lượng Kiểm Thử: 10 lần
Kết Quả: Đánh giá thời gian đáp ứng và xác thực thành công hoặc thất bại.
Bước 2: Tạo Người Dùng Mới

Mô tả: Kiểm tra tính năng tạo người dùng mới bằng cách gửi yêu cầu POST với thông tin người dùng mới.
Số Lượng Kiểm Thử: 5 lần
Kết Quả: Đánh giá thời gian xử lý yêu cầu và kết quả thành công hoặc thất bại.
4. Kết Quả Kiểm Thử
Bước 1: Xác thực Người Dùng
Thời Gian Đáp Ứng Trung Bình: 250ms
Tỷ Lệ Xác Thực Thành Công: 90%
Tỷ Lệ Xác Thực Thất Bại: 10%
Bước 2: Tạo Người Dùng Mới
Thời Gian Xử Lý Trung Bình: 500ms
Tỷ Lệ Tạo Người Dùng Thành Công: 80%
Tỷ Lệ Tạo Người Dùng Thất Bại: 20%
5. Phát Hiện và Ghi Chú
Thời gian đáp ứng và xử lý trong phạm vi chấp nhận được cho tất cả các bước kiểm thử.
Tỷ lệ xác thực và tạo người dùng mới cần được theo dõi để xác định và giải quyết các vấn đề xác thực hoặc tạo người dùng.
6. Kết Luận
Bằng cách sử dụng Postman, chúng tôi đã thực hiện kiểm thử API và đánh giá tính năng cũng như hiệu suất của ứng dụng. Kết quả này sẽ hỗ trợ quá trình cải thiện và tối ưu hóa API để đảm bảo trải nghiệm người dùng tốt nhất.

