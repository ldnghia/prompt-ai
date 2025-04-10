# 🤖 Tích hợp AI vào quy trình review code trước khi tạo Pull Request

## ✅ Mục đích
Hướng dẫn dev sử dụng AI để **review code trước khi tạo PR**, nhằm:
- Tự kiểm tra lỗi logic, format, đặt tên
- Gợi ý refactor, tách file
- Giảm tải cho reviewer chính thức

---

## 🪜 Quy trình gợi ý

1. **Xem lại toàn bộ code thay đổi**
   - Tự rà lại các đoạn logic chính đã sửa
   - Tập trung vào hàm mới, component mới, hook...

2. **Dán vào AI với prompt phù hợp**  
   Sử dụng prompt:
   ```plaintext
   Hãy review đoạn code sau trước khi tôi tạo pull request. Gợi ý giúp tôi nếu có vấn đề về logic, clean code, hoặc có thể tách nhỏ:

   [CODE HERE]
