# Ứng Dụng Quản Lý Thông Tin Sinh Viên

## Giới Thiệu  
Ứng dụng này cho phép người dùng nhập và gửi thông tin sinh viên từ `MainActivity` sang `SecondActivity`.  
Các thông tin bao gồm:  
- **Họ và tên**  
- **Mã số sinh viên (MSSV)**  
- **Lớp**  
- **Số điện thoại (SDT)**  
- **Sinh viên năm mấy** (Lựa chọn qua RadioButton)  
- **Chuyên ngành** (Lựa chọn qua CheckBox)  
- **Kế hoạch phát triển bản thân**  

## Tính Năng  
Nhập thông tin sinh viên từ `MainActivity`  
Gửi dữ liệu sang `SecondActivity`  
Hiển thị thông tin đã nhập tại `SecondActivity`  
 

## Cấu Trúc 
- activity_main.xml # Giao diện màn hình nhập thông tin  <br>
- activity_second.xml # Giao diện màn hình hiển thị thông tin  <br>
- MainActivity.java # Xử lý nhập và gửi dữ liệu  <br>
- SecondActivity.java # Xử lý nhận và hiển thị dữ liệu <br>
 

## Ghi Chú  
- Nếu không chọn năm học hoặc chuyên ngành, ứng dụng sẽ hiển thị "Không".  
- Dữ liệu được truyền qua `Intent` giữa các Activity.  


<br>

**21200026 - Nguyen Truong An**.   
