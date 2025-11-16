#Mô phỏng Hệ thống Mạng Doanh nghiệp – 100 Người dùng
Dự án mô phỏng mạng doanh nghiệp với 100 nhân sự sử dụng phần mềm Cisco Packet Tracer. Hệ thống được chia theo từng bộ phận bằng VLAN, đồng thời tích hợp các dịch vụ mạng cần thiết như DHCP, DNS, Web, Email và FTP server để mô phỏng môi trường văn phòng thực tế.
#Thành phần chính
-100 người dùng, chia thành các phòng ban: Giám đốc, Kế toán, Nhân sự, ...
-VLAN: chia tách mạng logic cho từng phòng ban để tăng tính bảo mật
-DHCP Server: cấp phát địa chỉ IP động tự động
-DNS Server: phân giải tên miền nội bộ
-Web Server: mô phỏng hệ thống quản lý thông tin công ty
-Email Server: hỗ trợ gửi và nhận mail giữa các nhân viên
-FTP Server: chia sẻ tệp nội bộ
-Routing OSPF: cấu hình Router để các thiết bị có thể liên lạc
-Access Control List (ACL): phân quyền truy cập giữa các VLAN (nếu có)
#Công cụ sử dụng
-Cisco Packet Tracer (phiên bản 8.22 trở lên)
-Thiết bị: PC, Laptop, Printer, Router, Switch Layer 2/3, PC, Server...
#Tệp dự án
network100.pkt – Tệp mô phỏng hệ thống mạng doanh nghiệp (100 users)
#Cách sử dụng
-Mở file network100.pkt bằng Cisco Packet Tracer (phiên bản 8.2.2)
-Kiểm tra ip,interface.... VLAN, DHCP, DNS,...
-Ping thử giữa các thiết bị, kiểm tra email và upload/download từ FTP
#Tác giả
Họ tên: Vũ Trường Vỹ
Email: vutrvy2003@gmail.com
#Dự án cá nhân: nhằm nâng cao kỹ năng mạng và quản trị hệ thống
#Ghi chú
Dự án mang tính mô phỏng và học tập, chưa triển khai thực tế.
