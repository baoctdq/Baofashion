# Baofashion – Shop Thời Trang Trẻ

> Bài tập lớn A3 · FIT4014 Thiết kế web và triển khai hệ thống phần mềm  
> Sinh viên: **Phạm Quốc Bảo** · Mã SV: _(2071020024)_ · Lớp: **CNTT20_02**  
> GVGD: ThS. Lê Thái Bảo · ĐH Đại Nam

---

## Giới thiệu

**Baofashion** là website thương mại điện tử thời trang trẻ được xây dựng bằng HTML5 và CSS3 thuần (không framework), thiết kế responsive theo hướng Mobile-first.

| Mục | Thông tin |
|-----|-----------|
| **Repository** | _(dán URL GitHub sau khi push)_ |
| **Website** | _(dán URL GitHub Pages sau khi deploy)_ |
| **Phiên bản** | v1.0.0 |
| **Ngày hoàn thành** | 25/11/2026 |

---

## Cấu trúc thư mục

```
Baofashion/
├── index.html        ← Trang chính (single-page, nhiều section)
├── ket-qua.html      ← Trang kết quả form liên hệ
├── css/
│   └── style.css     ← Toàn bộ CSS (reset, layout, component, responsive)
├── assets/           ← Chứa hình ảnh sản phẩm (thêm vào khi có ảnh thật)
├── README.md         ← Tài liệu dự án (file này)
└── AI_log.md         ← Nhật ký sử dụng AI
```

---

## Các tính năng

| Tính năng | Mô tả |
|-----------|-------|
| **Hero section** | Banner chính với CTA, số liệu nổi bật |
| **Features** | 5 cam kết dịch vụ (freeship, đổi trả, v.v.) |
| **Danh mục** | 4 danh mục sản phẩm dạng card với hover effect |
| **Sản phẩm** | Grid 8 sản phẩm mẫu, filter tab (UI), badge Sale/Mới |
| **Flash Sale banner** | Countdown đếm ngược thời gian thật (JavaScript) |
| **Testimonials** | 3 đánh giá khách hàng |
| **Form liên hệ** | HTML5 validation, submit về `ket-qua.html` via GET |
| **Footer** | Đa cột với link nhanh, mạng xã hội |
| **Back-to-top** | Nút xuất hiện khi scroll ≥ 400px |
| **Active nav** | Highlight menu tương ứng với section đang xem |
| **Responsive** | Breakpoint 1024px, 768px, 480px |

---

## Cách mở

### Chạy local
```bash
# Mở trực tiếp trong trình duyệt
# Nhấn đôi vào index.html HOẶC dùng Live Server (VS Code)
```

### Deploy lên GitHub Pages
```bash
git init
git add .
git commit -m "feat: Baofashion A3 FIT4014 initial release"
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
# Vào Settings → Pages → Source: main branch → /root → Save
# URL: https://<username>.github.io/<repo>/
```

> **Lưu ý đường dẫn tương đối**: Các link `css/style.css`, `assets/*` dùng đường dẫn tương đối (không có `/` đầu) để hoạt động đúng trên GitHub Pages sub-path.

---

## Kỹ thuật HTML5/CSS3 được áp dụng

- **Semantic HTML5**: `<header>`, `<main>`, `<footer>`, `<nav>`, `<section>`, `<article>`
- **CSS Grid** & **Flexbox** cho layout đa cột
- **CSS Custom Properties** (biến màu sắc)
- **CSS Transitions** cho hover effect
- **CSS `clamp()`** cho font size fluid
- **CSS `aspect-ratio`** cho ảnh sản phẩm
- **Media queries** (max-width: 1024px / 768px / 480px)
- **HTML5 Form validation**: `required`, `minlength`, `maxlength`, `type="email"`, `type="tel"`, `pattern`
- **Accessibility cơ bản**: `aria-label`, `aria-describedby`, `role`, semantic markup, focus-visible
- **JavaScript thuần**: Countdown timer, Intersection Observer (active nav), filter tab

---

## Giới hạn đã biết

- Giỏ hàng là UI-only, không lưu dữ liệu thật
- Form submit qua GET (query string) – không gửi email thật
- Hình ảnh sản phẩm dùng emoji placeholder – cần thay bằng ảnh thật
- Chưa tích hợp backend / cơ sở dữ liệu
- Filter tab chưa lọc sản phẩm thật (UI only)

---

## Nguồn tài nguyên

| Tài nguyên | Nguồn | Giấy phép |
|------------|-------|-----------|
| Font Inter | Google Fonts | OFL |
| Emoji icons | Hệ thống (Unicode) | Miễn phí |
| Mã HTML/CSS | Tự viết | — |
| AI hỗ trợ | Antigravity (Google DeepMind) | Khai báo trong AI_log.md |
