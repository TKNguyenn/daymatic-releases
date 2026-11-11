# Daymatic

Daymatic giúp quản lý lịch làm việc và ghi giờ công theo các task đã xác minh.

Repo này chỉ chứa hướng dẫn, thông tin phiên bản và các file app phát hành. Source code được lưu trong một repo private riêng.

## Tải app

Các bản được phát hành nằm trong [Releases](https://github.com/TKNguyenn/daymatic-releases/releases).

- **Windows:** dùng bộ cài `Daymatic-Setup-<version>.exe` khi có bản phát hành.
- **Ubuntu Desktop 24.04 x64:** dùng `Daymatic-<version>-ubuntu-24.04-x86_64.tar.gz`, giữ nguyên cả thư mục sau khi giải nén.

Nếu chưa có file cho hệ điều hành của bạn trong Releases, bản đó chưa được phát hành. Không tải các file Source code ZIP/tar.gz tự sinh của GitHub: chúng chỉ chứa tài liệu của repo này.

## Dùng trên Ubuntu

Đăng nhập desktop bằng tài khoản người dùng bình thường, mở khóa GNOME login keyring, rồi chạy `Daymatic gui`. Không chạy bằng sudo. Xem `README-Ubuntu.md` trong gói app để cài thư viện hệ thống và thiết lập lịch chạy.

Lịch, lịch sử và dữ liệu Ubuntu nằm trong `~/.local/share/AutoTimesheet` nếu bạn không đổi `XDG_DATA_HOME`. Tài khoản và khóa mã hóa phiên được lưu trong keyring của máy. Chuyển từ Windows sang Ubuntu cần đăng nhập và Preview lại.

Luôn kiểm tra đúng project/task bằng Preview và xác nhận trước khi bật tự động. Không bật đồng thời hai bản app trên hai hệ điều hành cho cùng tài khoản.

## Cập nhật

Tải bản mới từ Releases và làm theo hướng dẫn đi kèm. Repo phát hành là nơi phân phối bản app; bản hiện tại chưa có cơ chế tự tải/cài cập nhật trong ứng dụng.
