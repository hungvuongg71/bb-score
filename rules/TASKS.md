1. Thiết lập cấu trúc cơ bản (Base Structure)
   [ ] Khởi tạo file index.html duy nhất (All-in-one).
   [ ] Khai báo cấu trúc HTML5 và Meta Viewport hỗ trợ Mobile/Tablet.
   [ ] Thiết lập CSS cho nền đen (#000) và hiệu ứng LED Neon (Cam/Đỏ).

2. Xây dựng giao diện (UI/UX) - Digital Style
   [ ] Thiết kế Input nhập tên cho Team Home và Team Away.
   [ ] Tạo khu vực hiển thị điểm số cực lớn (Score Display).
   [ ] Thiết kế khu vực hiển thị thời gian (Timer Display) ở trung tâm.
   [ ] Hệ thống nút Còi (Buzzer System):
   [ ] Nút Còi 1 (Whistle - Play): Nút bấm phát tiếng còi nhưng không ảnh hưởng đến đồng hồ.
   [ ] Nút Còi 2 (Whistle - Toggle): Nút bấm phát tiếng còi và thay đổi trạng thái đồng hồ (Dừng/Chạy).
   [ ] Responsive Design: Tự động tối ưu giao diện theo màn hình Dọc/Ngang.

3. Phát triển tính năng (Logic JS)
   3.1. Quản lý điểm số & Thời gian
   [ ] Viết hàm tính điểm: +1, +2, +3 cho mỗi đội.
   [ ] Set Timer: Cho phép nhập số phút thi đấu ban đầu (ví dụ: 10, 12 phút).
   [ ] Countdown Logic: Sử dụng setInterval để đếm ngược phút:giây.
   3.2. Logic Còi Trọng Tài (Mô tả âm thanh: Tiếng còi Fox 40 đanh, xé gió)
   [ ] Còi 1 (Còi thông báo): - [ ] Khi bấm: Phát tiếng còi trọng tài.
   [ ] Trạng thái đồng hồ: Không thay đổi (Nếu đang chạy thì vẫn chạy, đang dừng thì vẫn dừng).
   [ ] Còi 2 (Còi điều khiển trận đấu):
   [ ] Khi bấm lần 1: Phát tiếng còi + Tạm dừng đồng hồ (Dùng khi có lỗi/bóng ra biên).
   [ ] Khi bấm lần 2: Phát tiếng còi + Tiếp tục đếm ngược (Dùng khi bắt đầu lại trận đấu).
   [ ] Buzzer Tự động: Tự động phát tiếng còi dài khi đồng hồ về 00:00.

4. Tối ưu hóa & Hoàn thiện
   [ ] Tăng kích thước 2 nút còi (Touch-friendly) để thao tác nhanh không cần nhìn.
   [ ] Đảm bảo âm thanh phát ra tức thì (Low Latency) ngay khi chạm.
   [ ] Sử dụng localStorage để lưu: Điểm số, Tên đội và Thời gian còn lại.
