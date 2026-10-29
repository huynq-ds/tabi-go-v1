# TabiGo Next-Gen Landing Page (Creative Edition v2)
## Ứng Dụng Mua eSIM Du Lịch Quốc Tế 150+ Nước • 3M Ecosystem

---

### 1. Giới Thiệu
Dự án **TabiGo Showcase** là phiên bản Landing Page thế hệ mới được thiết kế đặc thù cho bài toán **kinh doanh & chuyển đổi mua eSIM (High CRO)** của hệ sinh thái 3M Telecom.

Phiên bản này khắc phục triệt để các nhược điểm của bản prototype trước đó (`https://tabigo-landing-v2.pages.dev/`), loại bỏ hoàn toàn mã Three.js WebGL cồng kềnh gây giật lag và thay thế bằng kiến trúc **Feather-Light 60 FPS**, bám sát 100% nghiệp vụ viễn thông du lịch.

---

### 2. Các Tính Năng Đột Phá Bán Hàng

1. **Hero Section 3D & Mockup iPhone 16 Pro:**
   - Cột trái: Headline sắc bén, 2 Store Badges (App Store, Google Play), QR Code khổ lớn quét tải App nhận mã `TABIGO10`.
   - Cột phải: Khung iPhone 16 Pro mockup nổi 3D lơ lửng hiển thị màn hình thật của TabiGo App kèm các Floating Stat Badges phát sáng: *SoftBank 5G 380 Mbps*, *Tiết kiệm -75% cước Roaming*, *1-Tap Kích hoạt 60s*.
2. **Bộ Tính Cước Tức Thì (Live eSIM Package Calculator):**
   - Cho phép người dùng chọn quốc gia (Nhật Bản, Hàn Quốc, Thái Lan, Singapore, Châu Âu, Mỹ, Đài Loan, Trung Quốc).
   - Kéo chọn số ngày (1 - 30 ngày) và chọn mức data (1GB/ngày, 2GB/ngày, Unlimited 5G).
   - Giá tiền VND tự động nhảy số theo thời gian thực (real-time price flip) kèm nhà mạng đối tác và điểm thưởng Tabi Points.
3. **Bộ Quét Nhận Diện Thiết Bị Tự Động (Device Compatibility Scanner):**
   - Tự nhận diện dòng máy người dùng đang duyệt web (User-Agent Detection) và báo ngay trạng thái hỗ trợ eSIM.
   - Hộp tra cứu nhanh danh sách các dòng iPhone, Samsung Galaxy, Google Pixel hỗ trợ eSIM.
4. **Khối So Sánh Nỗi Đau (Pain Points vs Solution):**
   - So sánh trực quan 3 rắc rối của SIM vật lý cũ vs Tiện ích eSIM 0 gram của TabiGo.
5. **Bộ Sưu Tập Điểm Đến HOT (Destinations Showcase):**
   - Thẻ điểm đến tuyệt đẹp với ảnh Unsplash chất lượng cao, quốc kỳ, tốc độ 5G và giá khởi điểm từ 25k/ngày.
6. **Quy Trình 3 Bước Cài Đặt (How It Works):**
   - 3 bước đơn giản như 3 con dấu thị thực hộ chiếu.
7. **Đặc Quyền 3M & Bảo Hiểm Du Lịch:**
   - Tặng kèm VPN du lịch miễn phí, tích điểm 10k = 1đ, cam kết hoàn tiền 100%, hỗ trợ 24/7.
8. **Voucher TABIGO10 & Chốt Đơn:**
   - Nút Sao chép mã 1 chạm (Click to copy) kèm thông báo trực quan.
9. **FAQ Accordion & Chân Trang Pháp Lý:**
   - 6 câu hỏi then chốt giải tỏa mọi băn khoăn, dấu chứng nhận Bộ Công Thương và hotline 24/7.

---

### 3. Cách Mở & Trải Nghiệm Ngay

Dự án sử dụng kiến trúc **Zero-Friction Single-File HTML Pro**. Bạn có thể trải nghiệm ngay lập tức mà không cần cài đặt dependencies:

```bash
# Cách 1: Mở trực tiếp trên trình duyệt
open tabi-go-showcase/index.html

# Cách 2: Chạy local server
cd tabi-go-showcase && npx serve . -l 3000
```
