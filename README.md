# Memory Matching Game

## Thông tin sinh viên
Tên: Nguyễn Nhật Minh

Mã số sinh viên: 24022818-CN15

## Giới thiệu game
Emoji Matching Game là trò chơi lật thẻ tìm cặp hình giống nhau, với nhiều cấp độ khó tăng dần và các yếu tố hấp dẫn như thẻ đặc biệt (x2, bomb), giới hạn thời gian

## Mức điểm đề xuất: 8
## Lý do bảo vệ mức điểm:
### Phát triển từ code mẫu và có bổ sung đáng kể:
Game được chia module rõ ràng (main menu, pause, game over, logic chơi, điểm số cao, cấp độ).

Tổ chức code dễ mở rộng và bảo trì.

### Đồ họa:
Sử dụng SDL2 để hiển thị ảnh emoji sinh động.

Các màn hình menu/pause/game over được xây dựng đầy đủ, trực quan.

### Âm thanh:
Có hiệu ứng âm thanh khi click nút và lật thẻ, tăng tính tương tác người chơi.

### Gameplay nâng cao:
3 cấp độ khó: 2x2, 4x4, 6x6.

Có thanh thời gian đếm ngược cho mỗi cấp độ.

Thẻ đặc biệt: x2.png nhân đôi điểm, bomb.png thua ngay lập tức.

Tính điểm và lưu điểm cao nhất (high score) giữa các lượt chơi.

Có thể tạm dừng và tiếp tục game (phím ESC hoặc nút Pause).

###📄 Các tính năng tự bổ sung:
Quản lý trạng thái game (MENU, PLAYING, PAUSED, GAME_OVER) một cách chặt chẽ.

Hiển thị thời gian còn lại bằng thanh hiệu ứng.

Tự động khởi tạo màn chơi mới và reset các biến khi chơi lại.

Lưu điểm cao giữa các lượt chơi và hiển thị rõ ràng trong lúc chơi.

### Các kỹ thuật lập trình đã sử dụng
- Vòng lặp
- Mảng tĩnh
- Xâu
- Vector, con trỏ
- Xuất/nhập file
- SDL2 (SLD2_image, SDL2_mixer, SLD2_ttf)
- Kỹ thuật Texture font, Mouse event, Key event
- Kỹ thuật sử dụng hoạt ảnh (Sprites)
- Sound Effects and Music


### Kết luận
- Hình ảnh và âm thanh được tham khảo từ nhiều nguồn khác nhau và được chỉnh sửa để phù hợp với game, nhưng đa số được tham khảo từ: Openmoji.org, Freesound.org.
- Một số ứng dụng, trang web hỗ trợ làm đồ họa: Microsoft Paint, Canva...
- Hiểu cách thức hoạt động và tự viết một game.
- Biết cách quản lý code cho những chương trình lớn, tìm và xử lý các lỗi ẩn.
- Sử dụng tốt ngôn ngữ lập trình C++ và các thư viện SDL2 để làm nên một game.
- Chia nhỏ một project lớn thành những file nhỏ, những file nhỏ thành những class nhỏ hơn để thuận tiện cho quá trình code, quản lý và debug.
