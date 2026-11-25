## Thông tin sinh viên

- Họ và tên: Phạm Quốc Bảo
- Mã sinh viên – Lớp: _(2071020024 của bạn)_ – CNTT20_02
- Ngày thực hiện: 25/11/2026
- Link repository: _(https://baoctdq.github.io/Baofashion/)_
- URL website: _(https://github.com/baoctdq/Baofashion)_
- Tình huống: [x] Website của tôi (BaoFashion – Shop thời trang trẻ)

---

## 1. Nhận định của tôi trước khi hỏi AI

- **Vấn đề/yêu cầu**: Cần xây dựng website thương mại điện tử (shop quần áo) bằng HTML5/CSS3 thuần cho môn FIT4014.
- **Mong muốn và hiện tượng**: Muốn có layout đẹp, hiện đại, responsive và đúng yêu cầu rubric A3 (7 tiêu chí) mà không dùng framework CSS như Bootstrap.
- **Dữ kiện đã kiểm tra**: Đọc tài liệu hướng dẫn A3, xem mẫu portfolio CV từ file zip, xác định các section cần có (hero, sản phẩm, form liên hệ, v.v.).
- **Tôi nghi nguyên nhân khó**: Viết CSS responsive cho nhiều breakpoint từ đầu tốn nhiều thời gian nếu không có cấu trúc rõ ràng.
- **Vì sao**: CSS Grid + Flexbox phức tạp khi kết hợp nhiều component khác nhau (card, form, footer đa cột).

---

## 2. Tôi hỏi AI và nhận được gợi ý

- **Nguồn**: [x] Công cụ AI: Antigravity (Google DeepMind)
- **Câu hỏi/prompt tôi đã gửi**:

  > "dựa vào file zip làm ra web shop quần áo hoặc shop mua đồ trong fit4014 theo yêu cầu của đề thiếu thông tin thì hỏi tôi"

- **Thông tin bổ sung tôi cung cấp** (khi AI hỏi lại):
  - Thông tin SV: Phạm Quốc Bảo, CNTT20_02
  - Tên shop: BaoFashion – Thời trang trẻ
  - Cấu trúc: Single-page (nhiều section)
  - Màu sắc: Đen/Trắng/Vàng – phong cách hiện đại
  - Cần đủ file A3: README, AI_log

- **Gợi ý/kết quả của AI**:
  - AI đọc file zip (portfolio CV mẫu) và tài liệu hướng dẫn A3 (PDF, DOCX)
  - AI phân tích rubric 7 tiêu chí và cấu trúc mẫu có sẵn
  - AI sinh ra toàn bộ: `index.html`, `ket-qua.html`, `css/style.css`, `README.md`, `AI_log.md`
  - Áp dụng: CSS Grid, Flexbox, responsive 3 breakpoint, HTML5 form validation, Intersection Observer, countdown timer

---

## 3. Quyết định của tôi

- [ ] Chấp nhận kết quả AI sinh ra làm điểm khởi đầu
- [x] Chỉnh sửa thêm rồi áp dụng
- [ ] Bác bỏ


- **Lý do**: Code tuân thủ đúng yêu cầu rubric A3, dùng HTML5/CSS3 thuần, có đầy đủ semantic HTML, responsive, và form validation theo đề bài.

---

## 4. Thực hiện và kiểm chứng

- **Tệp/vị trí đã tạo**:
  - `index.html` – Trang chính single-page
  - `ket-qua.html` – Trang kết quả form
  - `css/style.css` – Toàn bộ stylesheet
  - `README.md` – Tài liệu dự án
  - `AI_log.md` – File này

- **Nội dung thay đổi sau khi nhận code từ AI**:
  - _(Điền các thay đổi bạn tự sửa thêm: thay emoji bằng ảnh thật, cập nhật URL, thêm sản phẩm, v.v.)_

| Nội dung kiểm tra | Trước xử lý | Sau xử lý |
|-------------------|-------------|-----------|
| Responsive trên mobile 375px | _(kiểm tra sau khi thêm ảnh)_ | _(điền kết quả)_ |
| Form validation (email sai format) | _(kiểm tra)_ | _(điền kết quả)_ |
| Countdown timer chạy | _(kiểm tra)_ | _(điền kết quả)_ |
| GitHub Pages load CSS đúng | _(sau khi deploy)_ | _(điền kết quả)_ |

- **Cách thử lại**: Mở Live Server (VS Code), kiểm tra DevTools ở độ rộng 375px / 768px / 1280px. Thử submit form với dữ liệu hợp lệ và không hợp lệ.

---

## 5. Kết luận

- [ ] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- **Điều tôi rút ra**: _(Điền sau khi hoàn thành kiểm thử và deploy – ví dụ: học được cách dùng CSS Grid cho layout đa cột, cách dùng Intersection Observer để highlight menu khi scroll, v.v.)_
