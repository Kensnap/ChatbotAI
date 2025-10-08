Link dự án: https://drive.google.com/drive/folders/1NUhHlPT9U0ad_lqDs8VSPY5CE68H4pzJ?usp=drive_link
# ChatbotAI
Dự án chatbot local dùng để hỏi đáp và truy xuất dữ liệu nội bộ trong tổ chức
- Ưu điểm:
+ Chạy local
+ Tính bảo mật cao
+ Độ chính xác của thông tin cao
+ tiết kiệm chi phí
+ không cần gpu
- Nhược điểm:
+ thời gian chờ lâu (có thể cải tiến bằng cách dùng gpu)

**!lưu ý:**
- trong mỗi file sẽ có đường liên kết tới dữ liệu để có thể vừa xem vừa chạy thử

**Hướng dẫn sử dụng:
**

B1: tải tất cả dữ liệu về
B2: thêm dữ liệu của tổ chức ở thư mục data
B3: chạy code trong file prepare_vector_db.ipynb để tạo vectorstore
B4: Vào QAchatbot.ipynb tạo prompt và bắt đầu tra cứu
