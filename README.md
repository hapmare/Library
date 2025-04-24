# Library Management System 📚
Thành viên nhóm: 
+ Lê Anh Huy: 22022126 Viết JUNIT TEST , hỗ trợ xây dựng models
+ Lưu Công Hải: 22022179 Thiết kế giao diện người dùng
+ Nguyễn Đức Việt: 22022195 Xử lý yêu cầu cơ sở dữ liệu , liên kết các API

**Giới thiệu** <br>
HHV Library Management System là một hệ thống quản lý thư viện hỗ trợ các chức năng như quản lý người dùng, mượn sách, tìm kiếm sách và gửi thông báo qua email. Hệ thống giúp dễ dàng quản lý các tài liệu và người dùng thư viện một cách hiệu quả.

Ứng dụng được xây dựng bằng JavaFX, sử dụng thư viện JFoenix cho giao diện người dùng và các công nghệ khác như Jakarta Mail cho việc gửi email thông báo.

# Các tính năng chính

**Quản lý người dùng:** <br>
Thêm, sửa, xóa thông tin người dùng. <br>
Tìm kiếm người dùng dựa trên mã ID.<br>

**Quản lý sách:** <br>
Thêm, sửa, xóa thông tin sách. <br>
Tìm kiếm sách dựa trên mã ID.<br>
Xem chi tiết thông tin từng cuốn khi click.<br>
Có thể thêm sách trực tiếp vào kho sau khi tìm kiếm sách từ Google Books API 

**Quản lý mượn sách(Phát hành sách và trả sách):**

-Phát hành sách: <br>
Nhập ID sách, ID người dùng để phát hành cuốn sách đó cho người dùng. <br>
Sau khi phát hành thì sẽ có thông báo qua email về việc gia hạn mượn sách cho người dùng.
-Trả sách: <br>
Nhập ID sách, ID người dùng để trả sách đó cho người dùng. <br>

**Tìm kiếm sách:**

Tìm kiếm sách từ Google Books API và hiển thị kết quả tìm kiếm trong giao diện.

**Gửi email thông báo:**

Gửi email thông báo cho người dùng về tình trạng mượn sách và các thông báo khác.

 Programming Language: Java<br>
 GUI Framework: JavaFX<br>
 Database: Apache Derby<br>
 Build Tool: Maven<br>
 Version Control: Git

# Cách sử dụng

**1. Quản lý người dùng**

+ Thêm người dùng: Nhấn nút "Add User" để thêm người dùng mới vào hệ thống.
+ Chỉnh sửa thông tin người dùng: Chọn người dùng từ danh sách và nhấn nút "Edit User" để chỉnh sửa thông tin.
+ Xóa người dùng: Chọn người dùng cần xóa và nhấn nút "Clear User". Hệ thống sẽ kiểm tra xem người dùng có mượn sách chưa trả hay không trước khi xóa.

**2. Quản lý sách**

+ Thêm sách: Nhấn nút "Add Book" để thêm sách mới vào hệ thống.
+ Chỉnh sửa thông tin sách: Chọn sách từ danh sách và nhấn nút "Edit Book" để chỉnh sửa thông tin.
+ Xóa sách: Chọn sách cần xóa và nhấn nút "Clear Book".
  
**3. Tìm kiếm sách**
+ Tìm kiếm sách: Nhập tên sách vào trường tìm kiếm và hệ thống sẽ tự động tìm kiếm các sách từ Google Books API.
+ Hiển thị kết quả: Kết quả tìm kiếm sẽ được hiển thị dưới dạng danh sách. Bạn có thể nhấn vào mỗi sách để xem chi tiết.
  
**4. Gửi email thông báo**
+ Thông báo mượn sách: Khi người dùng mượn sách, hệ thống sẽ tự động gửi email thông báo về việc gia hạn mượn sách.
+ Cấu hình email: Trong lớp MailSender, bạn có thể cấu hình thông tin tài khoản Gmail để hệ thống có thể gửi email.

**5. Đóng cửa sổ**
+ Thoát ứng dụng: Nhấn nút "Cancel" để đóng cửa sổ hiện tại của ứng dụng.

# UML diagram
![image](https://github.com/user-attachments/assets/e48a9763-4147-49df-8c0a-a0610ee263a0)

![image](https://github.com/user-attachments/assets/52cd6dc8-f7cb-4e28-a2c1-06bbf3a32cf0)


