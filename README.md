## VinCSS SK Manager Tool - Tính năng chính

- **Kết nối và hiển thị thông tin khóa bảo mật**: Tự động nhận diện và hiển thị các khóa bảo mật đang kết nối (tên, pin, vân tay, phiên bản firmware, dung lượng pin).
- **Quản lý PIN**: Thiết lập, thay đổi PIN (4-63 ký tự, hỗ trợ ký tự đặc biệt) cho khóa bảo mật.
- **Quản lý vân tay** *(chỉ cho VinCSS FIDO2 Fingerprint)*: Thêm, đổi tên, xóa vân tay (tối đa 5 vân tay).
- **Quản lý Bluetooth** *(chỉ cho VinCSS FIDO2 Fingerprint)*: Xem/chỉnh sửa tên thiết bị, PIN Bluetooth, xóa cache kết nối.
- **Quản lý Credential**: Xem, tìm kiếm, xóa từng hoặc toàn bộ credential đã lưu trên khóa.
- **Reset khóa bảo mật**: Đưa khóa về trạng thái mặc định, xóa toàn bộ dữ liệu/credential.
- **Cập nhật firmware**: Kiểm tra và nâng cấp firmware khóa bảo mật với 4 bước an toàn, hỗ trợ khôi phục khi lỗi hoặc mất kết nối.
- **Xem và gửi log**: Xem nhật ký hoạt động của khóa bảo mật, gửi phản hồi trực tiếp đến VinCSS.


## Hướng dẫn cài đặt VinCSS SK Manager Tool

### **Windows**
1. Tải bản cài đặt mới nhất cho Windows tại:
   [VinCSS SK Manager Tool - Windows](https://github.com/VinCSS-Public-Projects/vincss-fido2-key-manager/blob/main/windows/VinCSS-SK-Manager-Tool_windows_Setup_x64.exe)
2. Chạy file cài đặt, chọn **Create a desktop shortcut** → **Next**.
3. Chọn **Install** để bắt đầu cài đặt.
4. Sau khi cài đặt hoàn tất, chọn **Finish**.
5. **Lưu ý**:
   - Ứng dụng yêu cầu quyền **Administrator** để nhận diện khóa bảo mật.
   - Khóa bảo mật VinCSS hỗ trợ FIDO/FIDO2 và các thay đổi API.

---

### **macOS**
1. Tải bản cài đặt mới nhất cho macOS tại:
   [VinCSS SK Manager Tool - macOS](https://github.com/VinCSS-Public-Projects/vincss-fido2-key-manager/blob/main/macos/VinCSS%20SK%20Manager%20Tool%201.0.6.pkg)
2. Mở file cài đặt, chọn **Continue** → **Install**.
3. Nhập mật khẩu thiết bị hoặc xác thực vân tay để tiếp tục.
4. Chọn **Close** để hoàn tất quá trình cài đặt.
5. Mở ứng dụng sau khi cài đặt thành công.
6. **Lưu ý**:
   - Khi cài đặt, cần cấp quyền truy cập thư mục lưu trữ để ứng dụng ghi log hoạt động.
   - Ở phần **Input Monitoring**, có thể cấp hoặc từ chối quyền đọc bàn phím — không ảnh hưởng đến chức năng ứng dụng.
