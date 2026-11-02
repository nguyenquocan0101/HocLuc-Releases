# HocLuc

Kho này chỉ dùng để phát hành file cài đặt Android (APK) của app **HocLuc**. Mã nguồn của app được giữ trong một kho riêng tư, không nằm ở đây.

## HocLuc là gì

HocLuc là app học tập dành cho học sinh có tài khoản [HocLuc](https://hocluc.com):

- Hai máy tính khoa học chạy ngay trên điện thoại, không cần mạng.
- Trang chủ, Học tập, Công cụ (đồ thị hàm số, biểu đồ số liệu), Hồ sơ và Thành tích theo tài khoản HocLuc của bạn.

Bạn cần đăng nhập bằng tài khoản HocLuc. Sau khi đăng nhập, máy tính vẫn dùng được khi mất mạng.

Yêu cầu: Android 7.0 trở lên. HocLuc là app riêng, cài song song với app HocLuc Calculator cũ (nếu có) chứ không thay thế nó.

## Tải về

Bản mới nhất luôn ở đường dẫn cố định:

**<https://github.com/nguyenquocan0101/HocLuc-Releases/releases/latest/download/hocluc.apk>**

Ghi chú thay đổi của từng bản: xem mục [Releases](https://github.com/nguyenquocan0101/HocLuc-Releases/releases).

## Cài đặt lần đầu

HocLuc không phát hành qua Google Play, nên Android cần bạn cho phép cài app từ file APK:

1. Mở đường dẫn ở trên bằng trình duyệt trên điện thoại (ví dụ Chrome) và tải `hocluc.apk`.
2. Mở file vừa tải (chạm vào thông báo tải xong hoặc vào mục Tải xuống).
3. Nếu Android báo không được phép cài ứng dụng không rõ nguồn gốc, chọn **Cài đặt** rồi bật **Cho phép từ nguồn này** cho trình duyệt (hoặc trình quản lý file) bạn vừa dùng, sau đó quay lại.
   Android 7 không có mục này cho từng ứng dụng: vào **Cài đặt > Bảo mật** và bật **Nguồn không xác định**.
4. Chọn **Cài đặt**. Nếu Google Play Protect cảnh báo về ứng dụng chưa quen, chọn xem chi tiết rồi **Vẫn cài đặt**.
5. Mở HocLuc và đăng nhập bằng tài khoản HocLuc.

Tên các mục có thể hơi khác tùy hãng điện thoại.

## Cập nhật

Bạn chỉ cần cài thủ công một lần. Sau đó app tự kiểm tra bản mới khi được mở và có mạng:

- Khi có bản mới, app hiện thông báo kèm ghi chú thay đổi; app chỉ tải bản mới khi bạn bấm cập nhật.
- Lần đầu cập nhật, Android hỏi bạn có cho phép HocLuc cài ứng dụng không; mỗi lần cài, Android đều hỏi xác nhận. App không bao giờ tự cài khi chưa hỏi bạn.
- Bản mới cài đè lên bản cũ và giữ nguyên dữ liệu trong app.
- Máy tính vẫn dùng được khi không có mạng; chỉ việc kiểm tra và tải bản cập nhật mới cần mạng.

## An toàn

- Mỗi bản phát hành kèm file `update.json` ghi mã SHA-256 và kích thước của `hocluc.apk`, dùng để kiểm tra file tải về có đúng bản đã phát hành không.
- Mọi bản đều ký bằng cùng một chứng chỉ, vân tay SHA-256: `c077fb8f94d9e48167b6052c86bb5dfcc5869dd309ab21423c01bf8399f4dec2`. Android từ chối cài đè bản ký bằng khoá khác.
- Chỉ tải HocLuc từ đường dẫn trên trang này.

© 2026 hocluc.com
