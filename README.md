## Thông tin cá nhân
- Họ và tên: Viengsavanh Vilaphon
- mssv:Laos195087
- lớp:K56kmt
## đề tài
Theo dõi bảng xếp hạng của các đội thi đấu Futsal ThaiLeague
## 1.Cơ sở dữ liệu:
-- Bảng RANKS: Lưu trữ thống kê kết quả giải đấu.
 + id_rank: ID
 + team: Tên đội Futsal
 + wins: Số trận thắng
 + draws: Số trận hòa
 + losses: Số trận thua
 + played: Số trận đã hoàn thành
 + remaining: số trận còn lại
 + points: Điểm số
 + ranh: bảng xếp hạng
## Stored Procedures (SP_): SP_GetTopTeam: Lấy thông tin của 4 đội Futsal có số điểm cao nhất

 ## 2. Module đọc dữ liệu: Sử dụng Python và FastAPI để tạo một API để lấy dữ liệu từ trang web chuyên về Futsal hoặc dịch vụ API thương mại như FIFA
## Mô tả nguồn dữ liệu:

+ Sử dụng Web Scraping hoặc lấy dữ liệu qua API của các trang web chuyên về Futsal.
+ Dữ liệu bao gồm thông tin về giải đấu, trận đấu, điểm số, bảng xếp hạng
 ## 3.Node-RED: Xây dựng một chu trình trong Node-RED để tự động gọi API Python để lấy dữ liệu. Sau đó, xử lý dữ liệu và ghi dữ liệu vào cơ sở dữ liệu.

## 4. Web:

- Xây dựng một ứng dụng web để hiển thị dữ liệu từ cơ sở dữ liệu.
- Hiển thị danh sách các đội bóng, và bảng xếp hạng của các đội Futsal đó
- Sử dụng các công nghệ như HTML, CSS, JavaScript để tạo giao diện web.
