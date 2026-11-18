# AI REPO RADAR V2.3 – Vietnamese First

## Mở chương trình
1. Giải nén ZIP.
2. Mở `index.html` bằng Google Chrome hoặc VS Code Live Server.
3. Vào **Xếp hạng Repo**, tìm kiếm, nhấn **Phân tích**.
4. Popup mới **Giải thích tiếng Việt** hiển thị công dụng dự kiến từ dấu hiệu GitHub, yêu cầu máy và chi phí với cảnh báo các phần chưa kiểm chứng.
5. Muốn bản đọc hiểu README chuyên sâu, vào **Cài đặt & Màu sắc** nhập Gemini API key (tự tạo từ https://aistudio.google.com/api-keys). Sau đó mở repo và nhấn **Phân tích chuyên sâu bằng AI**.

## Các thay đổi V2.3
- Không mặc định đưa tiếng Anh dài vào phần giải thích; README tiếng Anh ẩn sau nút xem tài liệu gốc.
- Tách mô tả tiếng Việt sơ bộ bằng quy tắc khỏi báo cáo AI Online thực sự. Không có key thì không giả vờ đã dịch/đọc hiểu README.
- Báo cáo Gemini cấu trúc tiếng Việt: công dụng, tính năng có bằng chứng, tương thích i5-4570/16GB/GTX750Ti 2GB, chi phí, ứng dụng, rủi ro, điểm nếu đủ chứng cứ.
- Lưu tối đa 30 báo cáo AI gần đây trong localStorage trên trình duyệt, nút xoá báo cáo; không lưu API key.
- Không thay đổi các tính năng bảng xếp hạng, màu Cyber, biểu đồ, danh sách theo dõi, trạm văn phòng 3D.

## Chú ý
- AI cần Internet, API key và model hợp lệ; hạn mức/chi phí phụ thuộc tài khoản. Không nhúng key vào website công khai.
- Nếu GitHub báo 403/429, đợi hạn mức làm mới. Không coi dữ liệu 0 là dữ liệu thật.
- Phần tiếng Việt không có AI chỉ phân loại sơ bộ từ metadata/keywords, không khẳng định tính năng đã kiểm chứng.
- Chỉ gửi README/metadata công khai lên Google khi nhấn nút phân tích AI.
- Report lưu localStorage có thể mất khi xoá dữ liệu trình duyệt.
