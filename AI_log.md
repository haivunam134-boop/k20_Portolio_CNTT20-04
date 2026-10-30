không hiện ảnh 
không đúng đường dẫn
không hiện ảnh 
không đúng đường dẫn

## Báo cáo lỗi

- `index.html`: biểu mẫu còn các giá trị `___`. Nhãn họ tên `for="___"` không khớp với `id="fullname"`; trường email chưa có `type="email"` và `required`; các thuộc tính giới hạn ký tự và `aria-describedby` chưa được điền. Kiểm tra dữ liệu biểu mẫu vì thế không hoạt động đúng.
- `index.html`: còn một đoạn biểu mẫu trùng sau `</body>` và `</html>`, nằm ngoài cấu trúc HTML hợp lệ và có thể làm trang hiển thị nội dung thừa.
- `css/style.css`: còn các giá trị `___` trong selector và khai báo CSS nên các quy tắc tương ứng không hợp lệ hoặc bị trình duyệt bỏ qua. Có quy tắc hoàn chỉnh lặp lại phía dưới; chưa kiểm tra trực tiếp giao diện để xác định ảnh hưởng hiển thị.
- Ảnh: trong `index.html` không có thẻ `<img>` hoặc đường dẫn ảnh, nên hiện không có ảnh được khai báo. Chưa thể xác nhận đường dẫn ảnh sai.
- Đường dẫn `css/style.css` và `ket-qua.html` được tham chiếu trong trang và cả hai tệp đều tồn tại trong thư mục dự án.

Phạm vi: đã kiểm tra mã nguồn `index.html`, `css/style.css`, `ket-qua.html`. Chưa kiểm tra trên trình duyệt.
