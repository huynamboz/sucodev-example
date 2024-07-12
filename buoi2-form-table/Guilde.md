# Một số thẻ trong html
  ## Thẻ a
  - Thẻ a dùng để tạo ra một liên kết đến một trang web khác hoặc một tài nguyên khác.
  - Thuộc tính của thẻ a:
    - href: Đường dẫn đến trang web hoặc tài nguyên khác
    - target: Để mở liên kết trong một cửa sổ mới
    - title: Hiển thị một chú thích khi rê chuột vào liên kết
    - download: Tải xuống một tài nguyên khi nhấp vào liên kết

  ## Thẻ strong, b, em i
  - Thẻ strong: Dùng để làm nổi bật một phần văn bản
  - Thẻ b: Dùng để in đậm một phần văn bản
  - Thẻ em: Dùng để in nghiêng một phần văn bản
  - Thẻ i: Dùng để in nghiêng một phần văn bản

  ## Thẻ inline và block
  - Width của thẻ block là sẽ 100% chiều rộng của phần tử cha chứa nó
  - Thẻ inline sẽ bị hạn chế về CSS như margin-top margin-bottom, padding-top, padding-bottom… 
    khi sử dụng thẻ inline thì nên biết mà tuỳ trường hợp mà sử dụng, 
    có thể dùng CSS để biến thẻ inline thành block hoặc inline block
  - Khi các thẻ inline nằm cùng nhau thì nó sẽ nằm trên một hàng như tên gọi của nó là inline
  - Thẻ inline sẽ có độ rộng bằng nội dung mà nó chứa
  - Thẻ block sẽ có độ rộng full 100% phần tử cha chứa nó
  - Thẻ block không bị hạn chế về CSS
  - Vì nó full 100% phần tử cha chứa nó cho nên khi dùng thẻ block cùng với nhau thì tụi nó sẽ rớt xuống hàng

# Form trong html
- Bản chất của form là tập hợp các input, select, textarea, button, radio, checkbox, file, ... để người dùng nhập dữ liệu và gửi dữ liệu đó lên server
- Các thẻ form cần phải có thuộc tính action và method
  - action: Đường dẫn đến trang xử lý dữ liệu
  - method: Phương thức gửi dữ liệu lên server (GET hoặc POST)


* input
  Gồm các type:
  - text: Cho phép nhập dữ liệu dạng text
  - number: Cho phép nhập dữ liệu dạng số
  - date: Cho phép nhập dữ liệu dạng ngày tháng
  - time: Cho phép nhập dữ liệu dạng thời gian
  - datetime: Cho phép nhập dữ liệu dạng ngày tháng và thời gian
  - email: Cho phép nhập dữ liệu dạng email
  - phone: Cho phép nhập dữ liệu dạng số điện thoại
  - password: Cho phép nhập dữ liệu dạng mật khẩu
  ...

  * thuộc tính của thẻ input
    - id
    - class
    - name
    - type
    - placeholder
    - value
    - required
    ...

* Thẻ select
  Dùng để tạo ra một dropdown list
  * Thuộc tính selected: Đánh dấu một option mặc định được chọn

* button 
  Có các type:
  - submit: Gửi dữ liệu
  - reset: Xóa thông tin đã nhập trên form

# Table trong html
- Bảng (Table) là phần tử HTML thể hiện dữ liệu được sắp xếp theo hàng và cột tương tự như một bảng tính. Trong HTML, cấu trúc bảng có thể giúp các bạn dễ dàng sắp xếp các thành phần từ đơn giản đến phức tạp theo một cách hoàn chỉnh với đầy đủ về tiêu đề hàng, cột, tiêu đề hợp nhất,… 

- Nội dung hay dữ liệu của bảng sẽ được bao bọc bởi cặp thẻ chính là:
  - Thẻ <table>: Đây là thẻ chính để tạo ra một bảng trong HTML.
  - Thẻ `<tr>`: Đây là thẻ để tạo ra một hàng trong bảng.
  - Thẻ <td>: Đây là thẻ để tạo ra một ô trong bảng.
  - Thẻ `<th>`: Đây là thẻ để tạo ra một ô tiêu đề trong bảng.

  * Một table sẽ có 3 phần chính:
    - `<thead>`: Phần này sẽ chứa các thẻ `<th>` để tạo ra các ô tiêu đề của bảng.
    - `<tbody>`: Phần này sẽ chứa các thẻ `<tr>` để tạo ra các hàng của bảng.
    - `<tfoot>`: Phần này sẽ chứa các thẻ `<tr>` để tạo ra các hàng cuối cùng của bảng.

  * Table border
  * Table size
  * Table colspan & rowspan
