Bước 1: Phân tích lỗi (3 phần văn bản thừa thãi trong phản hồi cũ)
Khi dùng prompt lỗi "Hãy giải thích ngắn gọn các nội dung của Custom Instructions, Prompt Library, Prompt Injection", AI thường sinh ra phần mở đầu/kết thúc lan man, thiếu cấu trúc dễ dán báo cáo. Cụ thể có 3 phần văn bản thừa thãi sau:
Lời chào hỏi và dẫn nhập xã giao ở đầu câu trả lời: Ví dụ các câu như "Chào bạn! Rất vui được hỗ trợ bạn tìm hiểu về chủ đề thú vị này..." — không mang thông tin chuyên môn và làm tốn diện tích khi dán vào tài liệu học tập.

Phần diễn giải lan man, lặp ý hoặc ví dụ dài dòng không được yêu cầu: Ví dụ giải thích vòng vo nhiều đoạn văn dài cho từng khái niệm thay vì đi thẳng vào ý cốt lõi, khiến kết quả khó quét nhanh (scannable).

Lời kết và câu mời chào/đề xuất mở rộng ở cuối: Ví dụ các câu như "Hy vọng phần giải thích trên hữu ích cho bạn. Nếu cần mình giải thích sâu hơn hoặc làm thêm ví dụ thực tế, hãy cho mình biết nhé!" — làm loãng nội dung chính khi trích xuất dữ liệu cho báo cáo.

Bước 2: Prompt tối ưu (Có ràng buộc định dạng & cấm lời chào dẫn)

Plaintext
Tải mã xuống
Sao chép mã
Giải thích ngắn gọn 3 khái niệm sau: Custom Instructions, Prompt Library, Prompt Injection.

Ràng buộc bắt buộc:
- Không viết lời chào, lời mở đầu, câu dẫn nhập hay lời kết/xã giao ở đầu hoặc cuối câu trả lời.
- Bắt buộc trình bày 100% bằng gạch đầu dòng ngắn gọn, súc tích, mỗi khái niệm tối đa 2 ý chính.
- Đi thẳng vào định nghĩa và tác dụng cốt lõi để dán nhanh vào tài liệu học tập.
Kết quả phản hồi mẫu của AI từ Prompt tối ưu (Ngắn gọn, sạch chữ thừa)

Custom Instructions: Lưu cố định bối cảnh và quy tắc phản hồi cho mọi ô chat mới mà không cần nhập lại, giúp duy trì phong cách và định dạng nhất quán.

Prompt Library: Kho lưu trữ và phân loại các mẫu prompt chuẩn hóa (thường dùng biến số động như {{TEN_BIEN}}) để tái sử dụng nhanh và đồng bộ chất lượng.

Prompt Injection: Lỗ hổng bảo mật khi chèn chỉ thị độc hại vào đầu vào nhằm lừa AI bỏ qua hướng dẫn hệ thống hoặc quy tắc an toàn ban đầu