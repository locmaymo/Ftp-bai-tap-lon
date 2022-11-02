# Ftp
BÁO CÁO BÀI TẬP LỚN MÔN LẬP TRÌNH MẠNG
HỌC KỲ I NĂM HỌC 2018-2019
Nhóm: 10
Thành viên:
1.	Họ và tên : Lê Hải Quân  Mã sinh viên: B15DCCN428
2.	Họ và tên: Lương Thị Hồng Ngọc Mã sinh viên: B15DCCN396
Nội dung:
1.	Giới thiệu sơ lược về chủ đề
a.	Mục tiêu
-	Công cụ cho phép gửi nhận/file qua mạng theo mô hình client/server
-	Hỗ trợ đa luồng
-	Hỗ trợ 2 giao diện thư mục client và server và cho phép kéo thả
b.	Kết quả đã đạt được
-	Cho phép người  gửi, nhận file, xem file trên Server 
-	Server giới hạn nhận file với 1 số đuôi (vd: .txt, .mp3, .wav)
-	Lưu nhật ký ra log
-	Sử dụng giao diện
-	Hỗ trợ đa luồng
-	Việc gửi file có cả tính toán thời gian
-	Cho phép hủy tiến trình đang thực hiện gửi/ nhận file
c.	Hạn chế, hướng phát triển
-	Gửi 1 file bằng nhiều luồng
-	Không thông báo cho server khi hủy tiến trình gửi/ nhận
2.	Phân công công việc
TT	Họ tên	Các nội dung thực hiện	Đánh giá
1	Lê Hải Quân	Code backend	Hoàn tất
2	Lương Thị Hồng Ngọc	Thiết kế giao diện	Hoàn tất





3.	Quá trình thực hiện
TT	Phiên bản	Vấn đề	Xử lý	Tự đánh giá	Link tải
1	FTP_v1	- Cho phép client gửi, nhận file từ server
- Ghi log nhật ký
- Giới hạn định dạng file	Hoàn tất	Khá hoàn tất	https://github.com/jnp2018/02_10_FTPSERVER.git
2	FTP_v2.1	- Thiết kế dạng app base
- Sử dụng đa luồng
- Kéo thả file
- Gửi file bằng nhiều luồng
- Cho phép hủy hành động gửi/ nhận file	- Thiết kế dạng app base
- Sử dụng đa luồng	- Giao diện chưa tối ưu	https://github.com/jnp2018/N2_10_FTPServer.git
3	FTP_v2.2	Kéo thả file
- Gửi file bằng nhiều luồng
- Cho phép hủy hành động gửi/ nhận file	- Cho phép kéo thả file để gửi	Hoàn tất	https://github.com/jnp2018/N2_10_FTPServer.git
4	FTP_v2.3	Gửi file bằng nhiều luồng
- Cho phép hủy hành động gửi/ nhận file	- Cho phép hủy hành động gửi/ nhận file	Khi client hủy hành động, server không thông báo tới server	https://github.com/jnp2018/N2_10_FTPServer.git
5	FTP_v2_Final	- Thiết kế dạng app base
- Sử dụng đa luồng
- Kéo thả file
- Gửi file bằng nhiều luồng	Chưa cho phép gửi file bằng nhiều luồng		https://github.com/jnp2018/N2_10_FTPServer.git
					
					


