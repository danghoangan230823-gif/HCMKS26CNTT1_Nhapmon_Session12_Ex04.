# Bài 4 : Chuẩn hóa quy trình quản lý bệnh án điện tử
## Phần 1. Phân tích
- Yêu cầu Chức năng (FR): Quản lý thông tin bệnh nhân, module khám bệnh (EMR) kê đơn/chỉ định, và lịch sử điều trị.

- Yêu cầu Phi Chức năng (NFR): Bảo mật (Mã hóa AES-256, TLS 1.3, phân quyền RBAC), hiệu năng (uptime $99.9\%$, phản hồi $<2$s), và tuân thủ pháp lý y tế.
## Phần 2. Triển khai (Clinic-Cloud)
Xử lý bẫy Excel (1,000 hồ sơ):

Dùng Ctrl + T tạo Excel Table để AutoFilter không bị ngắt quãng.

Điền giá trị quy ước (None, N/A) vào các ô trống thay vì để khoảng trắng.

Donut Chart tối giản: Dùng tối đa 3 màu, đưa tổng số ca bệnh vào tâm biểu đồ.
## Phần 3. Kiểm thử & Khắc phục lỗi Heading
- **Lỗi:** Nhầm đoạn văn thành tiêu đề Heading làm rối mục lục.
- **Cách khắc phục:** Bôi đen đoạn lỗi $\rightarrow$ Nhấn Ctrl + Shift + N để đưa về định dạng Normal ban đầu.