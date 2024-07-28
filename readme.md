## Ứng Dụng Nén Ảnh

Đây là một ứng dụng web đơn giản cho phép người dùng nén ảnh xuống một mức dung lượng mong muốn tính bằng KB. Ứng dụng được xây dựng bằng HTML, CSS và JavaScript, sử dụng thư viện `browser-image-compression` để nén ảnh.

### Tính Năng

-   Chọn tệp ảnh từ thiết bị của bạn.
-   Nhập kích thước mong muốn cho ảnh đã nén tính bằng KB.
-   Theo dõi tiến trình nén ảnh với thanh tiến trình động.
-   Tải ảnh đã nén sau khi quá trình nén hoàn tất.
-   Hiển thị thông báo lỗi rõ ràng và hướng dẫn người dùng một cách trực quan.

### Cách Sử Dụng

1. **Chọn Ảnh**: Nhấn nút "Chọn ảnh" để chọn tệp ảnh từ thiết bị của bạn.
2. **Nhập Kích Thước Mong Muốn**: Nhập kích thước mong muốn cho ảnh đã nén vào ô "Kích thước mong muốn (KB)".
3. **Nén Ảnh**: Nhấn nút "Nén Ảnh" để bắt đầu quá trình nén.
4. **Theo Dõi Tiến Trình**: Theo dõi thanh tiến trình để biết tiến độ nén.
5. **Tải Ảnh Nén**: Sau khi quá trình nén hoàn tất, nhấn vào nút "Tải ảnh nén về" để tải ảnh đã nén về máy tính của bạn.

### Giải Thích Chi Tiết

Việc nén ảnh để đạt chính xác kích thước mong muốn có thể khó khăn vì nhiều yếu tố:

-   **Chất Lượng Gốc của Ảnh**: Ảnh có chất lượng cao với nhiều chi tiết sẽ khó nén hơn so với ảnh có ít chi tiết.
-   **Độ Phức Tạp của Ảnh**: Ảnh có nhiều chi tiết phức tạp (nhiều màu sắc, họa tiết) sẽ khó nén hơn ảnh có ít chi tiết.
-   **Giới Hạn của Thuật Toán Nén**: Các thuật toán nén ảnh sẽ cố gắng giảm kích thước bằng cách giảm chất lượng ảnh. Tuy nhiên, chúng có giới hạn và không phải lúc nào cũng đạt được kích thước mục tiêu một cách chính xác.
-   **Chất Lượng Được Thiết Lập Ban Đầu**: Chúng ta thiết lập chất lượng ảnh ban đầu (0.9 trong ví dụ này) và giảm dần cho đến khi đạt kích thước mong muốn hoặc đạt giới hạn chất lượng. Tuy nhiên, điều này không đảm bảo kích thước cuối cùng sẽ chính xác như mong muốn.
