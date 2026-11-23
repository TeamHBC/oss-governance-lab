# BẢN ĐỒ LỘ TRÌNH PHÁT TRIỂN (PROJECT ROADMAP)

Lộ trình này được rà soát định kỳ hàng quý bởi Hội đồng điều hành (Steering Committee).

## Giai đoạn Hiện tại (Now - Quý 1/2027)
- [x] Hoàn thiện quy chế quản trị cộng đồng (.github/GOVERNANCE.md) và bậc thang thăng tiến.
- [x] Tự động hóa phân loại Issue bằng GitHub Actions (issue-triage.yml) và Issue Template.
- [ ] Thiết lập hệ thống kiểm thử CI/CD tự động hóa đạt độ phủ Code Coverage tối thiểu 80%.
- [ ] Vá triệt để các lỗ hổng bảo mật P0 trong module xử lý chuỗi.

## Giai đoạn Tiếp theo (Next - Quý 2/2027)
- [ ] Triển khai định dạng Log JSON có cấu trúc theo bản đề xuất RFC-0001.
- [ ] Hỗ trợ đóng gói phân phối đa nền tảng (Linux, macOS, Windows ARM64).
- [ ] Bổ sung ít nhất 02 thành viên mới vào danh sách Reviewers/Triagers.

## Giai đoạn Tương lai (Later - Cuối năm 2027 trở đi)
- [ ] Nghiên cứu giải pháp biên dịch WebAssembly (Wasm) cho phiên bản chạy trực tiếp trên trình duyệt.
- [ ] Nộp hồ sơ gia nhập vườn ươm dự án của Quỹ CNCF (Cloud Native Computing Foundation Sandbox).

## Ngoài phạm vi (Out of Scope)
Dự án sẽ **không** làm các việc sau, để Contributor khỏi mất công gửi PR lạc đề:
- Không phát triển giao diện đồ họa (GUI) cho công cụ.
- Không hỗ trợ các phiên bản hệ điều hành đã hết vòng đời hỗ trợ chính thức.
- Không tích hợp dịch vụ thu thập dữ liệu người dùng (telemetry) mặc định.
