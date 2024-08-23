# Hệ Thống Quản Lý Tài Liệu Hướng Dẫn - Odoo

## Giới thiệu

Hệ thống quản lý tài liệu hướng dẫn cho người sử dụng (khách hàng) trong Odoo cho phép quản lý các loại tài liệu như PDF, Word, Excel, PowerPoint, và hình ảnh. Hệ thống hỗ trợ phân quyền truy cập và cho phép người dùng xem tài liệu dựa trên quyền của họ.

## Tài Liệu

### Các Loại Tài Liệu

Hệ thống hỗ trợ các loại tài liệu sau:

- PDF
- Word
- Excel
- PowerPoint
- Hình ảnh

### Thông Tin Tài Liệu

Mỗi tài liệu sẽ bao gồm các thông tin sau:

- **Avatar**: Hình ảnh đại diện của tài liệu.
- **Tên**: Tên của tài liệu.
- **Giới thiệu sơ lược**: Mô tả ngắn gọn về tài liệu.
- **Loại tài liệu (Category)**: Phân loại tài liệu theo danh mục (ví dụ: Hướng dẫn sử dụng, Tài liệu kỹ thuật).
- **Loại dữ liệu**: Loại dữ liệu mà tài liệu chứa (ví dụ: Văn bản, Hình ảnh).
- **Tài liệu dành cho nhóm nào**: Xác định nhóm người dùng nào tài liệu này hướng tới (ví dụ: Nhóm phát triển, Nhóm khách hàng).

## Phân Quyền

### Quyền Truy Cập

Chỉ những người dùng được phân quyền quản lý tài liệu mới có thể truy cập và cập nhật thông tin tài liệu. Quyền truy cập này được quản lý thông qua phân quyền trong Odoo.

### Quyền Quản Lý Tài Liệu

- **Người dùng có quyền quản lý**: Có thể thêm, chỉnh sửa, và xóa tài liệu.
- **Người dùng không có quyền quản lý**: Chỉ có thể xem tài liệu.

## Xem Tài Liệu

Người dùng có thể xem tài liệu qua giao diện người dùng như sau:

1. **Truy Cập Menu**: Nhấp vào biểu tượng Avatar của người dùng trên giao diện Odoo.
2. **Chọn "User Guides"**: Trong menu hiện ra, chọn "User Guides" để mở trang danh sách các tài liệu dành cho người dùng.

### Trang Danh Sách Tài Liệu

- Hiển thị danh sách các tài liệu mà người dùng có quyền xem.
- Cung cấp các thông tin cơ bản về mỗi tài liệu như tên, loại tài liệu, và giới thiệu sơ lược.
- Cho phép người dùng tải về hoặc xem tài liệu trực tiếp nếu tài liệu được hỗ trợ bởi trình duyệt.

## Cài Đặt và Cấu Hình

1. **Cài Đặt Mô Hình Dữ Liệu**: Đảm bảo mô hình dữ liệu của bạn được cấu hình để lưu trữ thông tin tài liệu và quyền phân quyền người dùng trong Odoo.
2. **Cấu Hình Phân Quyền**: Đảm bảo các quyền truy cập và quản lý tài liệu được cấu hình đúng cho từng nhóm người dùng trong Odoo.

## Hướng Dẫn Cài Đặt

1. **Cài Đặt Dependencies**: Đảm bảo bạn đã cài đặt tất cả các module và phụ thuộc cần thiết trong Odoo.
2. **Cấu Hình Mô Hình và Quyền**: Thiết lập mô hình dữ liệu và phân quyền truy cập trong Odoo theo hướng dẫn.

## Tài Liệu Tham Khảo

- [Tài liệu Odoo](https://www.odoo.com/documentation/)
- [Hướng dẫn về Odoo Development](https://www.odoo.com/documentation/15.0/howtos/)

## Liên Hệ

Nếu bạn có bất kỳ câu hỏi nào về hệ thống, vui lòng liên hệ với đội ngũ hỗ trợ qua email: support@example.com.
