# Tìm hiểu trước bài
## Lập trình hướng đối tượng là gì? Tính ứng dụng và lí do
- Lập trình hướng đối tượng là phương pháp lấy đối tượng để xây dụng chương trình
(là phương pháo lập trình dựa trên kiến túc của class và object)
- Giúp sử dụng lại code, tiết kiệm tài nguyên
- Sửa lỗi dễ dàng, dễ quản lí
- Có tính bảo mật cao, bảo đảm thông tin
- Dễ mở rộng dự án
## Khái niệm về Class và object trong OOP? Sự khác nhau?
### Đối tượng
- Đối tượng là thực thể: nhóm xe có xe honda, mec,..
- Đối tượng gồm 2 thông tinh: thuộc tính và phương thức
  + Thuộc tính là những thông tin, đặc điểm của đối tương: một người sẽ có: tên, ngày sinh,...
  + Phương thức là những thao tác mà đối tượng có thể thực hiện được: một người có thể ăn, ngủ,...
### Lớp
- Các đối dượng có chung đặc tính được gom lại thành 1 lớp: Lớp động vật, lơp con người
- Trong lớp có 2 thành phần chính là thuộc tính và phương thức
- Lớp được định nghĩa các kiểu dữ liệu mới tương tự struct nhưng cao cấp hơn
### sự khác nhau
- Lớp là khuôn mẫu còn đối tượng là một thể hiện cụ thể của khuôn mẫu đó:
  + Ví dụ: class là car thì object sẽ là toyota,honda,mec,..
## 4 TÍnh chất chính của lập trình hướng đối tượng
### Tính đóng gói (Encapsulation)
- Các dữ liệu và phương thức có liên quan đến nhau được đóng gói thành lớp để dễ quản lí và sự dụng
- Che giấu một số thông tin và những tính chất xử lý bên trong của đối tượng.
### Tính trừu tượng
- Loại bỏ những thứ phúc tạp không cần thiết chỉ tập trung vào cốt lõi của đối tượng
### Tính kế thừa
- Lớp cha chia sẽ các dữ liệu và phương thức cho lớp con và các lớp con không cần phải định nghĩa lại 
- Lớp con có thể kế thừa hoặc bổ sung thêm các thành phần mới
- Ví dụ: Lớp cha là smartphone thuộc tính là màu, bộ nhớ, lớp con iphone,samsung cũng có các thuộ tính màu, bộ nhớ
### Tính đa hình
- Cho phép các đối tượng khác nhau thực thi chức năng giống nhau theo những cách khác nhau