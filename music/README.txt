DANH SÁCH NHẠC NỀN
==================

1. Chép các file nhạc MP3 của bạn vào thư mục này.
   Ví dụ: our-love-theme.mp3

2. Mở file src/config/musicConfig.ts và cập nhật danh sách "tracks":
   - id      : mã bài nhạc
   - title   : tên bài (hiển thị trong bảng điều khiển)
   - artist  : tác giả / ca sĩ (không bắt buộc)
   - src     : đường dẫn bắt đầu bằng /music/ten-file.mp3
   - volume  : âm lượng 0..1
   - loop    : phát lặp hay không

3. Nếu muốn mỗi chương một bài khác nhau, cập nhật mục "perChapter"
   trong cùng file, trỏ tới "id" tương ứng.

Lưu ý:
- Nhạc KHÔNG tự phát khi tải trang. Nhạc chỉ bắt đầu sau khi
  người xem bấm mở hộp quà ở Chương 1 (theo đúng quy định của trình duyệt).
- Nếu file nhạc chưa tồn tại, website KHÔNG bị lỗi. Bảng điều khiển
  sẽ hiển thị "Chưa có nhạc".
