# Hướng Dẫn Sử Dụng Script Tạo Giọng Nói trong Google Sheets

## Giới Thiệu

Đây là một script đơn giản được viết bằng Apps Script cho phép tạo giọng nói từ văn bản trong Google Sheets bằng dịch vụ Text-to-Speech (TTS) của OpenAI. Script sẽ lặp qua các dòng dữ liệu trong bảng tính và tạo tệp âm thanh từ văn bản được cung cấp.

## Cách Sử Dụng

### Bước 1: Chuẩn Bị

1. **API Key:**
   - Để sử dụng script, bạn cần có API Key từ OpenAI. Đăng ký tài khoản và tạo API Key cho dịch vụ Text-to-Speech (TTS) trên trang OpenAI.

2. **Google Sheet ID:**
   - Lấy ID của Bảng tính Google bạn muốn sử dụng bằng cách sao chép chuỗi ký tự dài trong URL giữa '/d/' và '/edit'.

3. **Google Drive Folder ID:**
   - Lấy ID của thư mục trong Google Drive mà bạn muốn lưu trữ các tệp âm thanh. Bạn có thể tìm thấy ID này trong liên kết của thư mục.

### Bước 2: Thêm Script vào Google Sheets

1. Mở Bảng tính Google của bạn.
2. Điều hướng đến Extensions > Apps Script.
3. Dán mã script được cung cấp vào trình soạn thảo.
4. Thay thế 'API Key', 'Google Sheet ID', và 'Folder ID' trong mã script với thông tin thực của bạn.

### Bước 3: Chạy Script

1. Mở bảng tính Google đã cài đặt script.
2. Trong bảng tính, chọn menu `Tạo ÂM Thanh`.
3. Chọn `Generate Speech` để chạy script và tạo giọng nói từ văn bản trong bảng tính.

## Lưu Ý

- Luôn bảo mật API Key và thông tin cá nhân.
- Đảm bảo rằng bạn đã cấp quyền truy cập cho script để truy cập dữ liệu trong Google Sheets và lưu trữ tệp trong Google Drive.

