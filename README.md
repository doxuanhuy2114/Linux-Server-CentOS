# Triển khai máy chủ Linux – CentOS Stream 9

## Mô tả
Triển khai và cấu hình máy chủ Linux trên môi trường ảo hóa VMware,
bao gồm SSH, Web Server và Firewall.

## Môi trường
- OS: CentOS Stream 9
- Ảo hóa: VMware Workstation
- IP máy ảo: 192.168.146.130

## Các bước thực hiện
1. Cài đặt CentOS Stream 9 trên VMware
2. Cập nhật hệ thống: dnf update
3. Cấu hình SSH - kết nối từ Windows vào máy ảo
4. Cài đặt Apache HTTP Server
5. Cấu hình Firewalld cho phép HTTP, HTTPS, SSH
6. Deploy trang web tĩnh

## Kết quả
- SSH thành công từ máy thật vào máy ảo
- Trang web truy cập được qua trình duyệt
- Firewall chỉ mở đúng các port cần thiết

## Công nghệ sử dụng
- CentOS Stream 9
- VMware Workstation
- Apache HTTP Server
- OpenSSH
- Firewalld
