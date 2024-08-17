# Interview

1. Flutter là gì?

- open-source UI software development kit do Google tạo ra. Nó có thể được sử dụng để tạo ứng dụng đa nền tảng.

2. Dart là gì?
  
- là ngôn ngữ lập trình được sử dụng để phát triển các ứng dụng Flutter.

3. Lợi ích khi sử dụng Flutter?

- Flutter giảm lượng mã thông qua tính năng Hot Reload, cho phép phát triển ứng dụng nhanh hơn.
- Nó hỗ trợ việc phát triển đa nền tảng, cho phép bạn viết mã cho cả IOS và Android
- Flutter tối ưu hóa tốt cho các ứng dụng di động 2D

4. Hạn chế của Flutter?

- Kích thước ứng dụng: lớn so với ứng dụng được viết bằng Kotlin hoặc Swift
- Thư viện bên thứ ba: Flutter đang phát triển nên có thể sẽ gặp khó khăn khi tìm kiếm các thứ viện bên thứ ba để tích hợp 
- hiệu suất: có thể sẽ chậm so với ứng dụng native
- học hỏi và chuyển ngôn ngữ: quen với java hoặc swift thì sẽ cần thời gian và công sức khi đổi sang học Dart

5. Hãy giải thích cấu trúc của Flutter?

- widget là cốt lõi: trong flutter mọi thứ đều là widget. widget là thành phần giao diện cơ bản nhất tạo nên toàn bộ giao diện người dùng của ứng dụng, bản thân ứng dụng cũng là một widget
- Cấu trúc thư mục: 
  - folder quan trọng nhất là lib (có file source code main.dart). Đây là nơi bạn tạo ra các file .dart và viết code
  - hai folder là android và ios dùng cho việc triển khai ứng dụng trên các nền tảng tương ứng

6. Kể cách tính năng quan trọng của Flutter?

- Hot reload: thay đổi mã nguồn có thể xem ngay kết quả không cần khởi động lại ứng dụng
- AOT Compiler: giúp biên dịch mã nguồn thành mã máy trước khi chạy ứng dụng
- giao diện người dùng linh hoạt: có thể tùy chỉnh các widget để thích nghi với nhiều thiết bị và kích thước màn hình khác nhau
- hỗ trợ nhiều widget
- đa nền tảng: phát triển được ứng dụn cho ios, android cùng một mã nguồn
- hiệu năng cao

7. Kể tên một số trình soạn thảo (editor) tốt nhất cho Flutter?

- vs code

8. Bạn hiểu thế nào về Streams

- 

9.  Kể tên một số loại hình khác nhau của Streams

-

10.   Bạn hiểu như nào về Flutter SDK

- là bộ công cụ phát triển giao diện người dùng đa nền tảng

11.  Sự khác nhau giữa Hot reload và hot restart

- Hot reload: không chạy lại hàm main(), initState(), sử dụng trong chế độ debug, cho phép thấy thay đổi ngay sau khi sửa lỗi, xây dựng giao diện người dùng và thêm tính năng mà không cần chạy lại ứng dụng từ đầu
- Hot restart: xóa trạng thái của ứng dụng, đặt lại trạng thái mặc định

12. Giải thích BuildContext là gì

-

13. Làm thế nào để tạo Https request trong Flutter

-

14. Kể tên 2 loại cơ sở dữ liệu thường dùng trong Flutter

-

15. Bạn hiểu như nào về tween animation

-

16. Phân biệt Stateless Widget và Stateful Widget
    - Stateless: không thay đổi trạng thái sau khi được tạo ra (VD: hiển thị văn bản tĩnh)
    - Stateful: có trạng thái và có thể thay đổi khi được tạo ra (VD: biểu mẫu đăng nhập)
17. Lifecycle của Widget là gì
    - gồm các giai đoạn: create, build, update, dispose
18. Kể tên một số widget thông dụng trong flutter
    - Container, Column, Text, Stack, Row, ListView, SingleChildScrollView, GridView
