👤 Người 1: Frontend (Giao diện & trải nghiệm người dùng)

👉 Phù hợp nếu mạnh HTML/CSS/JS

Công việc chính:

Thiết kế giao diện:

Trang chủ (phim mới, phim hot)

Trang danh sách phim

Trang chi tiết phim

Trang xem phim

Trang đăng nhập / đăng ký

Cắt giao diện từ Figma (nếu có)

Responsive (PC, tablet, mobile)

Hiệu ứng JS:

Slider phim

Tìm kiếm gợi ý

Kết nối dữ liệu từ backend (qua PHP, AJAX)

Công nghệ:

HTML, CSS, JS

Bootstrap / Tailwind

Fetch / Ajax

Sản phẩm bàn giao:

Bộ giao diện hoàn chỉnh

Template PHP (header, footer)

👤 Người 2: Backend (PHP xử lý logic)

Người 2 – Backend (Xử lý logic PHP)

Vai trò:
Phụ trách xây dựng toàn bộ hệ thống xử lý phía server (Backend), chịu trách nhiệm về logic nghiệp vụ, bảo mật, kết nối cơ sở dữ liệu và cung cấp dữ liệu cho frontend.

1. Xây dựng cấu trúc dự án

Thiết kế cấu trúc project PHP theo mô hình MVC (Model – View – Controller) ở mức cơ bản.

Phân tách rõ ràng các thành phần xử lý nghiệp vụ, truy vấn cơ sở dữ liệu và giao diện.

Cấu trúc đề xuất:

app/
 ├── controllers/
 ├── models/
 ├── views/
 ├── config/
 └── helpers/

2. Chức năng xác thực và phân quyền người dùng

Xây dựng chức năng đăng ký, đăng nhập, đăng xuất người dùng.

Mật khẩu được mã hóa bằng các thuật toán hash đảm bảo an toàn.

Quản lý phiên đăng nhập bằng Session.

Phân quyền người dùng:

Admin: Quản lý phim (thêm, sửa, xóa).

User: Xem phim và tìm kiếm phim.

Kiểm soát quyền truy cập, đảm bảo người dùng không truy cập trái phép các chức năng quản trị.

3. Quản lý phim (CRUD)

Xây dựng các chức năng:

Thêm phim mới

Chỉnh sửa thông tin phim

Xóa phim

Hiển thị danh sách phim

Lưu trữ thông tin phim trong cơ sở dữ liệu MySQL.

Tăng lượt xem mỗi khi người dùng truy cập trang xem phim.

4. Upload và quản lý video

Hỗ trợ upload video phim hoặc nhập link phim.

Kiểm tra và giới hạn định dạng file video cho phép.

Giới hạn dung lượng file upload.

Đổi tên file trước khi lưu để tránh trùng lặp và tăng tính bảo mật.

5. Tìm kiếm và lọc phim

Xây dựng chức năng tìm kiếm phim theo tên.

Hỗ trợ lọc phim theo tiêu chí (thể loại, lượt xem…).

Tối ưu truy vấn để đảm bảo hiệu năng hệ thống.

6. Kết nối và xử lý cơ sở dữ liệu

Kết nối cơ sở dữ liệu MySQL bằng PDO.

Sử dụng Prepared Statement để chống SQL Injection.

Xử lý lỗi khi truy vấn hoặc kết nối cơ sở dữ liệu.

7. Xử lý bảo mật và kiểm tra dữ liệu

Validate dữ liệu đầu vào từ form (rỗng, sai định dạng).

Lọc và làm sạch dữ liệu người dùng nhập vào.

Ngăn chặn các lỗ hổng bảo mật phổ biến như SQL Injection, XSS.

Thiết lập session timeout và xử lý logout an toàn.

8. Xây dựng các hàm và API nội bộ

Xây dựng các hàm xử lý nghiệp vụ backend như:

Kiểm tra đăng nhập

Kiểm tra quyền admin

Tìm kiếm phim

Lấy thông tin phim theo ID

Cập nhật lượt xem

Các hàm được tổ chức riêng biệt, dễ bảo trì và mở rộng.

9. Logging và xử lý lỗi

Ghi log các hoạt động quan trọng như đăng nhập và thao tác quản lý phim.

Xử lý lỗi hệ thống và hiển thị thông báo thân thiện cho người dùng.

10. Sản phẩm bàn giao

Source code backend PHP hoàn chỉnh.

Cơ sở dữ liệu MySQL và file script tạo bảng.

Các hàm xử lý nghiệp vụ backend.

Tài liệu mô tả chức năng backend phục vụ tích hợp frontend.
 Database + Admin + Nội dung 

👉 Phù hợp người cẩn thận, logic

Công việc chính:

📦 Cơ sở dữ liệu

Thiết kế CSDL:

users

movies

categories

episodes

comments

views / ratings

Viết script tạo bảng (SQL)

Tối ưu truy vấn

🛠️ Trang Admin

Quản lý phim

Quản lý thể loại

Quản lý user

Duyệt/báo cáo lỗi

🧪 Kiểm thử & báo cáo

Test toàn bộ chức năng

Ghi bug, đề xuất cải tiến

Viết báo cáo thuyết trình

Sản phẩm bàn giao:

File .sql

Tài khoản admin mẫu

Báo cáo & slide 🧑‍🤝‍🧑 BẢNG PHÂN CÔNG CÔNG VIỆC NHÓM (3 NGƯỜI)

Thông tin chung
Tên đề tài: Website xem phim trực tuyến (WEBPHIM)

Công nghệ: PHP, MySQL, HTML, CSS, JavaScript

Quản lý mã nguồn: GitHub

Bảng phân công chi tiết STT Họ và tên Vai trò Nhiệm vụ chính Nhánh Git 1 Frontend - Thiết kế giao diện trang chủ, trang danh sách phim, trang xem phim
Thiết kế form đăng nhập/đăng ký
Xử lý HTML, CSS, JavaScript, Bootstrap frontend 2 ………………… Backend - Xây dựng logic hệ thống bằng PHP
Xử lý đăng nhập, phân quyền
CRUD phim, thể loại
Kết nối cơ sở dữ liệu backend 3 ………………… Database & Admin - Thiết kế cơ sở dữ liệu MySQL
Tạo các bảng và dữ liệu mẫu
Xây dựng trang quản trị (admin)
Kiểm thử hệ thống database
Cách thức làm việc nhóm
Mỗi thành viên làm việc trên nhánh Git riêng

Sau khi hoàn thành chức năng, code được merge về nhánh main

GitHub được sử dụng để theo dõi tiến độ và lịch sử làm việc của các thành viên

📌 Bảng này bạn có thể chụp ảnh trang GitHub Branch để minh chứng.

🌿 HƯỚNG DẪN MERGE BRANCH KHÔNG BỊ CONFLICT

👉 Làm đúng các bước này thì 99% không bị lỗi.

🔹 Nguyên tắc vàng (RẤT QUAN TRỌNG)

Không sửa chung 1 file cùng lúc (ví dụ: index.php)

Mỗi người làm đúng phần của mình

Luôn pull main mới nhất trước khi merge

