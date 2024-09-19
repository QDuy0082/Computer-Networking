# Ứng dụng điều khiển máy tính từ xa

## 1. Giới thiệu
Ứng dụng có chức năng giống **TeamViewer**, có thể dùng một máy để điều khiển màn hình máy khác thông qua chuột, bàn phím.

## 2. Demo video
[Link video demo](https://youtu.be/g3SVFKiqwxk)

## 3. Công nghệ sử dụng
Ứng dụng được viết bằng **C++** với các thư viện sau:
- **SDL2** và **DearImGui** cho giao diện.
- **OpenCV** để xử lý ảnh (nén, giải nén,...).
- **WinSock2** để thiết lập socket phục vụ cho truyền, nhận ảnh.

## 4. Chức năng
- **Server:** Chọn một máy client đã kết nối vào mạng LAN để thiết lập kết nối.
- **Client:** Cho phép một client kết nối với server và chia sẻ màn hình.
- **Điều khiển từ xa:** Thực hiện các thao tác chuột và bàn phím trên máy client từ máy server.
- **Chụp màn hình liên tục:** Chụp màn hình máy client và gửi tới máy server để hiển thị.
- **Xử lý hình ảnh:** Sử dụng OpenCV để nén và giải nén hình ảnh trước khi truyền.
- **Bảo mật:** Hỗ trợ mã hóa dữ liệu truyền qua mạng để đảm bảo an toàn.

## 5. Cách sử dụng
1. Tải, cài đặt và mở file trên cả hai máy tính.
2. Kết nối cả hai máy tính vào cùng một mạng LAN.
3. Mở ứng dụng trên máy muốn làm server và chọn một client từ danh sách các thiết bị đã kết nối.
4. Bắt đầu điều khiển máy client từ server.

## 6. Đóng góp
Nếu bạn muốn đóng góp cho dự án, vui lòng gửi pull request hoặc mở issue trên GitHub.

## 7. Liên hệ
Nếu có bất kỳ thắc mắc hoặc góp ý nào, bạn có thể liên hệ với tôi qua [22120082@student.hcmus.edu.vn]
