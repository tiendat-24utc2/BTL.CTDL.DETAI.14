# BTL.CTDL.DETAI.14
Trình đánh giá và chuyển đổi biểu thức toán học
 Giới thiệu đề tài
- Bối cảnh:
Mọi ngôn ngữ lập trình và phần mềm tính toán đều phải trả lời câu hỏi: làm thế nào để
máy tính hiểu và tính đúng một chuỗi ký tự như 3 + 4 ∗ 2/(1 − 5)? Chuỗi này chứa số,
toán tử và ngoặc; thứ tự thực hiện phụ thuộc vào độ ưu tiên của toán tử, tính kết hợp và
dấu ngoặc. Nếu chỉ tính tuần tự từ trái sang phải sẽ cho kết quả sai.
- Mục tiêu đề tài:
Xây dựng chương trình C++ có khả năng:
. Đọc biểu thức trung tố do người dùng nhập, kiểm tra tính hợp lệ
. Chuyển đổi sang các dạng (hậu tố, tiền tố, trung tố chuẩn hóa và mã LATEX)
. Tính giá trị biểu thức, hỗ trợ biến và các hàm toán học thông dụng
. Biểu diễn biểu thức dưới dạng cây và hiển thị cây
. Hiển thị từng bước tính toán (trạng thái ngăn xếp) để phục vụ học tập
. Lưu và đọc lại lịch sử tính toán bằng tệp văn bản.
- Phạm vi và giới hạn:
Chương trình làm việc với số thực kiểu double; hỗ trợ năm toán tử hai ngôi (+, −, ∗, /,
%), lũy thừa, dấu âm một ngôi và tám hàm một đối số. Các nội dung nằm ngoài phạm
vi gồm: nhân ngầm (2x), hàm nhiều đối số (max(a, b)), số phức và biến đổi ký hiệu (đạo
hàm, rút gọn). Những nội dung này được đề xuất ở phần hướng phát triển.
- Ý nghĩa:
Về mặt học thuật, đề tài giúp vận dụng trực tiếp ngăn xếp và cây nhị phân vào một bài
toán thực tế [?, 2]. Về mặt ứng dụng, các kỹ thuật này là nền tảng của trình thông dịch,
trình biên dịch, máy tính khoa học và bảng tính.
