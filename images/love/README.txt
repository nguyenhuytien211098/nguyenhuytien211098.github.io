THƯ MỤC ẢNH CỦA HAI VỢ CHỒNG
=============================

1. Chép ảnh của bạn vào thư mục này.
   Nên dùng tên đơn giản, không dấu, không khoảng trắng:
   photo-01.jpg, photo-02.jpg, chuyen-di-da-lat.jpg ...

2. Mở file src/data/albumData.ts và điền đường dẫn vào trường "src":
   src: "/images/love/photo-01.jpg"

3. Các trường có thể chỉnh cho từng ảnh:
   - title       : tiêu đề ảnh
   - caption     : chú thích (hiển thị dạng chữ viết tay)
   - date        : ngày tháng (ví dụ "2021")
   - album       : "polaroid" | "timeline" | "cinematic" | "floating"
                   (ảnh thuộc phân cảnh nào ở Chương 2)
   - orientation : "landscape" | "portrait" | "square"
   - alt         : mô tả thay thế cho trình đọc màn hình
   - focus       : { x, y } điểm lấy nét (0..1) giúp tránh cắt vào mặt
                   ví dụ { x: 0.5, y: 0.35 }

4. ẢNH CHIẾM BAO NHIÊU CŨNG ĐƯỢC.
   Website hỗ trợ hàng trăm ảnh. Ảnh ở mosaic (Chương 3) sẽ tự động
   lặp lại nếu số ảnh ít hơn số ô của trái tim.

5. Nếu chưa có ảnh, website vẫn chạy bình thường:
   hệ thống tự tạo ảnh giữ chỗ màu hồng - vàng rất đẹp.

6. Nên nén ảnh (WebP hoặc JPEG chất lượng ~80%) và giữ kích thước
   cạnh dài khoảng 1200–2000px để website tải nhanh.
