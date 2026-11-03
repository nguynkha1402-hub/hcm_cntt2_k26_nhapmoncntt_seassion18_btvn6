### 1. Phân tích (Nút thắt cổ chai)

- Ảnh quá nặng làm nghẽn băng thông.
- Lỗi đứt link (404) làm mất hình ảnh bản đồ và lãng phí thời gian kết nối của trình duyệt.   

### 2. Triển khai (3 bước tối ưu)

- Sửa lỗi 404: Cập nhật lại đường dẫn URL chuẩn xác để tài nguyên nhận mã 200 OK.
- Nén ảnh: Giảm kích thước, chuyển sang định dạng web hiện đại (WebP).
- Bật Browser Cache: Cấu hình Header để lưu tài nguyên tĩnh (CSS, JS, Image) xuống bộ nhớ đệm thiết bị.

### 3. Kiểm thử (Mã 304 Not Modified)

-Đây là tín hiệu tốt vì máy chủ báo tài nguyên không đổi. Trình duyệt sẽ lấy thẳng dữ liệu từ bộ nhớ đệm (cache) thay vì tải lại, giúp tiết kiệm tối đa băng thông và trang load tức thì