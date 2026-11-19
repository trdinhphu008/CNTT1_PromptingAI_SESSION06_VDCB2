# 1.Khắc phục lỗi khai báo biến số trong prompt mẫu
### Bước 1: Phân tích lỗi
Em nhận thấy việc sử dụng hai kiểu biến `[language]` và `[audience]` gây khó khăn vì:

1.  Không thống nhất cách khai báo biến
    
2.  AI khó nhận diện chính xác vị trí cần thay thế thông tin
    
 3.  Khó tự động hóa khi sử dụng prompt cho nhiều đối tượng và ngôn ngữ khác nhau

### Bước 2: Đồng bộ biến số

Em sửa prompt thành:

Hãy viết một bài chia sẻ về chủ đề ứng dụng AI trong học tập và nghiên cứu bằng ngôn ngữ dành cho đối tượng 

Yêu cầu:

-   Sử dụng ngôn ngữ phù hợp với đối tượng
    
-   Nội dung rõ ràng, dễ hiểu
    
-   Giữ nguyên cấu trúc biến để dễ dàng thay thế thông tin
