# QUY CHẾ QUẢN TRỊ DỰ ÁN (PROJECT GOVERNANCE)

Dự án này vận hành theo mô hình **Đồng thuận mở (Consensus-Seeking)** kết hợp với chế độ **Công trạng kỹ thuật (Meritocracy)**[cite: 12]. Mô hình này được lựa chọn nhằm khuyến khích sự đóng góp dựa trên năng lực thực tế và đảm bảo các quyết định quan trọng có sự đồng thuận rộng rãi của tập thể, tránh tình trạng tập trung quyền lực tuyệt đối vào một cá nhân như mô hình BDFL (Benevolent Dictator for Life).

## 1. Bậc thang thăng tiến (Contributor Ladder)[cite: 12]

### Cấp 1: Community Contributor (Người đóng góp cộng đồng)[cite: 12]
- **Điều kiện:** Đã có ít nhất 01 Pull Request được duyệt và gộp vào dự án (mã nguồn, tài liệu, hoặc kiểm thử)[cite: 12].
- **Quyền hạn:** Được vinh danh trong danh sách thành viên đóng góp, có quyền tham gia góp ý kiến thảo luận các bản đề xuất kiến trúc (RFC)[cite: 12].

### Cấp 2: Reviewer / Triager (Người sàng lọc & Đánh giá)[cite: 12]
- **Điều kiện:** Có tối thiểu 05 PRs đóng góp chất lượng cao; tích cực hỗ trợ giải đáp thắc mắc và tái hiện lỗi trên Issue Tracker trong 30 ngày[cite: 12].
- **Quyền hạn kỹ thuật:** Được cấp quyền `Triage` trên GitHub Organization (quản lý nhãn Labels, chỉ định người giải quyết, đóng/mở Issue)[cite: 12].

### Cấp 3: Core Maintainer (Người bảo trì nòng cốt)[cite: 12]
- **Điều kiện:** Đóng góp bền bỉ trong ít nhất 3 tháng; nắm vững toàn diện kiến trúc dự án; được đề cử bởi 01 Maintainer hiện tại và đạt 100% đồng thuận[cite: 12].
- **Quyền hạn kỹ thuật:** Được cấp quyền `Write` trên GitHub (duyệt và gộp PR vào nhánh `develop`/feature; tạo thẻ Tag phiên bản; điều phối sprint)[cite: 12].

### Cấp 4: Steering Committee (Hội đồng điều hành tối cao)[cite: 12]
- **Cơ cấu:** Gồm 03 thành viên thường trực, nhiệm kỳ 01 năm, bầu cử dân chủ theo quy chế bỏ phiếu kín của cộng đồng Core Maintainers[cite: 12].
- **Quyền hạn kỹ thuật:** Được cấp quyền `Admin` (quản lý bí mật Secrets, quản trị tài sản số, xử lý báo cáo an ninh `SECURITY.md`, quyết định tranh chấp CoC)[cite: 12].
- **Quy định giai đoạn khởi tạo:** Trong giai đoạn khởi tạo, Project Lead tạm thời đảm nhiệm vai trò Steering Committee và sẽ mở rộng bầu cử chính thức khi dự án có đủ 03 Core Maintainer.

## 2. Cơ chế ra quyết định (Decision-Making)[cite: 5]
- **Đồng thuận tĩnh (Lazy Consensus):** Các đề xuất kiến trúc (RFC) hoặc thay đổi quan trọng được mở thảo luận công khai trong **72 giờ**[cite: 5, 12]. Nếu hết thời hạn này mà không có phiếu phủ quyết hợp lệ, đề xuất mặc định được thông qua[cite: 12].
- **Quy tắc biểu quyết:**
  - **`+1`:** Đồng ý và ủng hộ đề xuất[cite: 5].
  - **`0`:** Trung lập, không phản đối nhưng không trực tiếp tham gia triển khai[cite: 5].
  - **`-1` (Veto - Phủ quyết):** Phản đối đề xuất; phiếu `-1` chỉ hợp lệ khi nêu rõ **lý do kỹ thuật** và đề xuất **phương án thay thế** khả thi[cite: 5].

## 3. Tiêu chuẩn thành viên danh dự (Emeritus Status)[cite: 12]
- Maintainer không hoạt động liên tục trong 06 tháng sẽ được chuyển sang trạng thái danh dự (Emeritus Member)[cite: 12].
- Quyền ghi (`Write`/`Admin`) sẽ được thu hồi tạm thời để bảo vệ an toàn dự án, nhưng vẫn giữ nguyên vinh danh trong hồ sơ lịch sử[cite: 12].

## 4. Bộ quy tắc ứng xử (Code of Conduct)[cite: 5]
Mọi thành viên tham gia dự án bắt buộc tuân thủ quy tắc ứng xử được quy định chi tiết tại tệp [CODE_OF_CONDUCT.md](../CODE_OF_CONDUCT.md)[cite: 5].
