# Test CORS Enabled

Ứng dụng web đơn giản dùng để kiểm tra xem một API hoặc website có hỗ trợ **Cross-Origin Resource Sharing (CORS)** hay không.

## Chức năng

- Nhập URL của API hoặc website cần kiểm tra.
- Gửi yêu cầu HTTP GET bằng AJAX (jQuery).
- Hiển thị kết quả:
  - **CORS Enabled!**: Yêu cầu được thực hiện thành công, máy chủ cho phép truy cập từ domain khác.
  - **Error!**: Yêu cầu thất bại do CORS bị chặn hoặc URL/API không hợp lệ.

## Công nghệ sử dụng

- HTML5
- Bootstrap 4
- jQuery 3.4.1
- AJAX

## Cách hoạt động

1. Người dùng nhập URL cần kiểm tra.
2. Nhấn nút **Check**.
3. Ứng dụng gửi yêu cầu GET đến URL được chỉ định.
4. Nếu trình duyệt nhận được phản hồi hợp lệ từ máy chủ, thông báo **CORS Enabled!** sẽ được hiển thị.
5. Nếu yêu cầu bị từ chối hoặc gặp lỗi, thông báo **Error!** sẽ được hiển thị.

## Lưu ý

- Kết quả phụ thuộc vào chính sách CORS được cấu hình trên máy chủ đích.
- Một số API yêu cầu xác thực hoặc không hỗ trợ phương thức GET nên có thể trả về lỗi mặc dù CORS đã được bật.
- Công cụ này chỉ là bài kiểm tra cơ bản từ phía trình duyệt.

## Ví dụ sử dụng

- **URL:** `https://api.example.com/data`  
- **Result:** `CORS Enabled!`

## Cài đặt & Chạy

1. Tải về hoặc clone repository này.
2. Mở file `index.html` bằng trình duyệt.
3. Nhập URL cần kiểm tra và nhấn **Check**.

## Hình ảnh minh họa

![Giao diện kiểm tra CORS](image/screenshot.png)
