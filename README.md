# html5-tag

Tài liệu này dựa trên **&lt;Sách hướng dẫn cốt lõi về tiêu chuẩn web&gt;** Đây là một bản tóm tắt của một số trong số đó.
Cập nhật lần cuối: 26/08/2023

## Thành phần
* **&lt;html&gt;** Phần tử gốc của tài liệu, tất cả các phần tử HTML phải được chứa trong phần tử gốc
* **&lt;head&gt;** Bao gồm các phần tử bộ siêu dữ liệu tài liệu, tiêu đề tài liệu, kiểu và các phần tử javascript
* **&lt;body&gt;** phần tử nội dung của tài liệu

## Phần tử meta
* **&lt;title&gt;** Tiêu đề của tài liệu chỉ chứa văn bản
* **&lt;meta&gt;** Chứa nhiều thông tin tài liệu khác nhau &lt;
* **&lt;style&gt;** Khi được viết trực tiếp trong tài liệu css
* **&lt;link&gt;** Liên kết các tài liệu bên ngoài với các tài liệu
* **&lt;base&gt;** Xác định URL cơ sở cho đường dẫn tương đối trong tài liệu

## Yếu tố kịch bản
* **&lt;script&gt;** Khi chèn tệp JavaScript vào tài liệu hoặc mô tả mã
* **&lt;noscript&gt;** Xác định nội dung pullback để phân phát thay thế khi JavaScript không được hỗ trợ

## Phần tử phần
* **&lt;section&gt;** Khi xác định các phần nội dung có thể được tổ chức thành các chương, phần, v.v.
* **&lt;nav&gt;** Khi xác định điều hướng chính của tài liệu
* **&lt;article&gt;** Việc phân phối lại không liên quan khi bạn xác định nội dung độc lập đáng được phân phối lại dưới dạng nguồn cấp dữ liệu RSS.
* **&lt;aside&gt;** Khi xác định nội dung ít liên quan đến nội dung cơ thể
* **&lt;header&gt;** Khi xác định tiêu đề cho các trang, phần, v.v.
* **&lt;footer&gt;** Khi xác định chân trang của một trang, phần, v.v.
* **&lt;address&gt;** Khi xác định thông tin liên lạc
* **&lt;h1&gt; ~ &lt;h6&gt;** Khi xác định tiêu đề của khối nội dung

## Phần tử nhóm
* **&lt;div&gt;** Khi bạn muốn nhóm các khối nội dung không có ý nghĩa ngữ nghĩa như các khối nội dung mà do vấn đề về thiết kế hoặc phát triển
* **&lt;main&gt;** Khi xác định vùng nội dung chính của tài liệu, chỉ có một &lt;main&gt;
* **&lt;p&gt;** Khi xác định nội dung đoạn văn
* **&lt;ul&gt;** Khi đánh dấu danh sách không có thứ tự
* **&lt;ol&gt;** Khi đánh dấu một danh sách có thứ tự
* **&lt;li&gt;** Khi xác định các mục danh sách của danh sách có thứ tự hoặc không có thứ tự.
* **&lt;dl&gt;** Khi đánh dấu một danh sách các định nghĩa
* **&lt;dt&gt;** Tiêu đề thuật ngữ trong danh sách dứt khoát
* **&lt;dd&gt;** Bảng chú giải thuật ngữ trong danh sách dứt khoát
* **&lt;figure&gt;** Các phần tử bao gồm hình ảnh, âm thanh, video và bảng biểu
* **&lt;figcaption&gt;** Khi xác định chú thích cho nội dung chứa trong một phần tử
* **&lt;blockquote&gt;** Khi xác định khối nội dung được trích dẫn
* **&lt;pre&gt;** Khi bạn muốn hiển thị trên màn hình như ở định dạng đầu vào, chẳng hạn như dấu cách hoặc ngắt dòng
* **&lt;hr&gt;** Khi muốn tách chủ đề của một đoạn văn

## Phần tử văn bản
* **&lt;a&gt;** Khi chỉ định một siêu liên kết
* **&lt;em&gt;** Khi bạn muốn nhấn mạnh văn bản
* **&lt;strong&gt;** Khi bạn muốn mang lại ý nghĩa cho nội dung đặc biệt quan trọng
* **&lt;i&gt;** Biểu thị văn bản có ý nghĩa thay đổi tâm trạng từ biểu thức in nghiêng đơn giản. Dùng cho biệt ngữ, thành ngữ, suy nghĩ hoặc tên tàu
* **&lt;b&gt;** Làm đậm văn bản
* **&lt;mark&gt;** Khi bạn muốn đánh dấu văn bản
* **&lt;small&gt;** Được sử dụng cho nội dung văn bản nhỏ, chẳng hạn như thông tin bản quyền
* **&lt;abbr&gt;** Khi xác định chữ viết tắt
* **&lt;cite&gt;** Khi xác định các trích dẫn và tài liệu tham khảo cho tác phẩm
* **&lt;q&gt;** Khi xác định dấu ngoặc kép nội tuyến
* **&lt;time&gt;** Để xác định thông tin ngày và giờ có thể được hiểu hoặc xử lý một cách máy móc
* **&lt;date&gt;** Để xác định thông tin ngày và giờ có thể được hiểu hoặc xử lý một cách máy móc
* **&lt;code&gt;** Khi xác định mã nguồn
* **&lt;var&gt;** Khi xác định ý nghĩa của các biến, mã định danh, v.v. trong một chương trình
* **&lt;samp&gt;** Khi xác định thông báo trạng thái của hệ thống
* **&lt;kbd&gt;** Khi xác định ý nghĩa của các giá trị đầu vào bàn phím, v.v.
* **&lt;sup&gt;** Khi xác định chỉ số trên
* **&lt;sub&gt;** Khi xác định chỉ số dưới
* **&lt;s&gt;** Khi bạn muốn hiển thị gạch ngang trong văn bản
* **&lt;u&gt;** Để gạch chân văn bản
* **&lt;dfn&gt;** Có nghĩa là một thuật ngữ trong danh sách các định nghĩa
* **&lt;ruby&gt;** Khi chèn một phần tử Ruby
* **&lt;rp&gt;** có nghĩa là dấu ngoặc đơn Ruby trong phần tử Ruby
* **&lt;rt&gt;** Ý nghĩa văn bản Ruby trong thành phần Ruby
* **&lt;bdi&gt;** Khi xác định hướng của một số văn bản trong đoạn văn
* **&lt;bdo&gt;** Khi xác định hướng của văn bản (từ trái sang phải, từ phải sang trái)
* **&lt;span&gt;** Khi nhóm văn bản nội tuyến
* **&lt;br&gt;** khi bạn muốn bọc
* **&lt;wbr&gt;** Khi bạn muốn áp dụng ngắt dòng trong một đơn vị từ cụ thể
* **&lt;ins&gt;** Khi bạn muốn ngắt dòng
* **&lt;del&gt;** Khi đánh dấu nội dung đã xóa

## Chứa phần tử
* **&lt;img&gt;** khi chèn hình ảnh
* **&lt;iframe&gt;** Khi xác định khung nội tuyến
* **&lt;embed&gt;** Khi chèn một tệp bên ngoài để chạy dưới dạng plugin
* **&lt;object&gt;** Khi chèn một tệp bên ngoài để chạy dưới dạng plugin
* **&lt;param&gt;** &lt;object&gt; Khi chỉ định các tham số của một phần tử
* **&lt;video&gt;** Khi chèn nội dung video
* **&lt;audio&gt;** Khi chèn nội dung âm thanh
* **&lt;source&gt;** Khi chèn nội dung pullback cho video, âm thanh
* **&lt;track&gt;** Khi chèn phụ đề hoặc siêu dữ liệu của video và âm thanh
* **&lt;canvas&gt;** Khi chèn hình ảnh bitmap động
* **&lt;svg&gt;** Khi chèn hình ảnh dựa trên vector
* **&lt;map&gt;** Khi xác định bản đồ hình ảnh
* **&lt;area&gt;** Khi chỉ định vùng liên kết trong bản đồ hình ảnh
* **&lt;math&gt;** Khi chèn công thức toán

## Phần tử bảng
* **&lt;table&gt;** khi chèn bảng
* **&gt;caption&gt;** Khi xác định chú thích của bảng
* **&lt;colgroup&gt;** Khi xác định cột nhóm cho bảng
* **&lt;col&gt;** Khi xác định các cột của bảng
* **&lt;thead&gt;** Khi xác định hàng tiêu đề của bảng
* **&lt;tbody&gt;** Khi xác định hàng nội dung của bảng
* **&lt;tfoot&gt;** Khi xác định hàng chân trang của bảng
* **&lt;tr&gt;** Khi xác định các hàng của bảng
* **&lt;th&gt;** Khi xác định ô tiêu đề của bảng
* **&lt;td&gt;** Khi xác định ô nội dung của bảng

## Phần tử biểu mẫu
* **&lt;form&gt;** Khi đánh dấu vùng sẽ chứa định dạng biểu mẫu
* **&lt;fielset&gt;** Khi nhóm các biểu mẫu có liên quan với nhau
* **&lt;legend&gt;** Khi xác định mục đích của một biểu mẫu được nhóm

## Yếu tố tương tác
* **&lt;details&gt;** Xác định vùng có thể hiển thị hoặc ẩn tùy theo lựa chọn của người dùng
* **&lt;summary&gt;** Xác định chi tiết để hiển thị hoặc ẩn dưới dạng phần tử con của phần tử
* **&lt;dialog&gt;** Khi đánh dấu các cửa sổ bật lên yêu cầu người dùng nhập hoặc phản hồi
