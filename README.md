# MCU-course
## Day1
MCU buổi 1: Giới thiệu tổng quan về MCU
Đánh giá tổng quan:
Luân
Dũng
Nội dung bài học:
Git 
Các tìm hiểu cách sử dụng các hàm
Analog, digital
GPIO, UART. I2C -> debug (con board giao tiếp với máy tính ntn)
Bài tập về nhà
Nhà thông minh 
(Nhiệt độ, độ ẩm, ánh sáng,... )
Điều khiển thông qua internet (điện thoại app/ trang web).
Giao tiếp không dây (wifi, bluetooth, ble, …)
3 mcus, 
1 con đo nhiệt độ, độ ẩm (dht11) + màn hình LCD (i2c) -> giao tiếp 1 wire. 
1 con phát hiện người (HC-SR501) -> có người tự động bật đèn (LED) -> GPIO
1 con cảnh báo cháy (MQ2) -> còi, gửi email (gọi điện). -> kết nối wifi.

cơ sở dữ liệu thu thập dữ liệu từ cả 3 nodes (mesh). -> tạo một cái web để hiển thị các giá trị đo được. esp-mesh.
sử dụng nút -> khi nhấn sẽ tạo cảnh báo. nếu mà đang cảnh báo, có hú còi mà muốn dừng lại - ngắt.
Tự tìm hiểu trước về RTOS.
deadline: 20/1
