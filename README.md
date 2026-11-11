# Daymatic

Daymatic giúp quản lý lịch làm việc và ghi giờ công theo các task đã xác minh.

Repo này chỉ chứa hướng dẫn, thông tin phiên bản và các file app phát hành. Source code được lưu trong một repo private riêng.

## Tải app

Các bản được phát hành nằm trong [Releases](https://github.com/TKNguyenn/daymatic-releases/releases).

- **Windows x64:** tải `Daymatic-Setup-1.2.4.exe`, mở và làm theo trình cài đặt.
- **Ubuntu Desktop 24.04 x64 (amd64):** tải `Daymatic-1.2.4-ubuntu-24.04-amd64.deb`, mở bằng **App Center**, chọn **Install**, rồi mở Daymatic từ menu ứng dụng.

Nếu chưa có file cho hệ điều hành của bạn trong Releases, bản đó chưa được phát hành. Không tải các file Source code ZIP/tar.gz tự sinh của GitHub: chúng chỉ chứa tài liệu của repo này.

## Dùng trên Ubuntu

Máy cần mạng để trình cài đặt tải các thư viện còn thiếu và mật khẩu quản trị của máy để cài gói. App đã kèm Python và Chromium; người dùng không cần cài Python. Chỉ hỗ trợ Ubuntu Desktop 24.04 x64, chưa hỗ trợ ARM hoặc Ubuntu cũ hơn.

Nếu mở `.deb` không hiện App Center, chạy trong thư mục chứa file:

```bash
sudo apt install ./Daymatic-1.2.4-ubuntu-24.04-amd64.deb
```

Sau khi cài, đăng nhập desktop bằng tài khoản người dùng bình thường, mở Daymatic từ menu, đăng nhập tài khoản trong app và kiểm tra Preview trước khi bật tự động. Mở khóa GNOME login keyring nếu được yêu cầu. Không chạy app bằng sudo.

Lịch, lịch sử và dữ liệu Ubuntu nằm trong `~/.local/share/AutoTimesheet` nếu bạn không đổi `XDG_DATA_HOME`. Tài khoản và khóa mã hóa phiên được lưu trong keyring của máy. Chuyển từ Windows sang Ubuntu cần đăng nhập và Preview lại.

Luôn kiểm tra đúng project/task bằng Preview và xác nhận trước khi bật tự động. Không bật đồng thời hai bản app trên hai hệ điều hành cho cùng tài khoản.

Trong Cài đặt, dùng **Cài lịch Ubuntu** để cài lịch tự động. Máy phải bật và đăng nhập phiên desktop với keyring đã mở khóa. Đóng app trước khi nâng cấp. Trước khi gỡ bản Ubuntu, tắt tự động và gỡ lịch Ubuntu trong Cài đặt; gỡ gói vẫn giữ dữ liệu cá nhân/keyring.

## Cập nhật

Tải bản mới từ Releases và làm theo hướng dẫn đi kèm. Repo phát hành là nơi phân phối bản app; bản hiện tại chưa có cơ chế tự tải/cài cập nhật trong ứng dụng.
