4.2.2. Mô tả cấu trúc mã nguồn 
4.2.2.1. Thư mục assets/ 
Chứa các tài nguyên tĩnh phục vụ giao diện người dùng, bao gồm: 
• css_form_admin/: Chứa CSS dành cho trang quản trị (admin). 
• css_form_users/: Chứa CSS dành cho trang người dùng (user). 
• css_index/: CSS dùng chung cho trang chủ hoặc trang chính. 
• script_index/: Có thể chứa các file JavaScript dùng cho giao diện. 
4.2.2.2. Thư mục db/ 
• config.php: File cấu hình kết nối cơ sở dữ liệu (chứa thông tin host, database, 
username, password). 
40 
4.2.2.3. Thư mục frm/ 
Chứa các form giao diện và xử lý logic liên quan đến từng nhóm người dùng. 
• frm_admin/: Chứa giao diện và các file xử lý của admin. 
• frm_user/: Chứa giao diện và các file xử lý của user. 
• File login.php và process_login.php 
• login.php: Chứa giao diện đăng nhập cho user và admin. 
• process_login.php: Xử lý thông tin đăng nhập, kiểm tra thông tin trong database 
và điều hướng người dùng/admin về đúng giao diện của họ. 
4.2.2.5. Thư mục img/ 
• Chứa hình ảnh liên quan đến hệ thống, như avatar người dùng, hình minh họa vi 
phạm, logo,...
