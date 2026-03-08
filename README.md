# Portfolio Website

Portfolio website giống như thiết kế của Chris Tran.

## Cấu trúc file

- `index.html` - File HTML chính
- `style.css` - File CSS cho styling
- `profile.jpg` - Ảnh profile (cần thêm)
- `dependency-parsing.png` - Ảnh dependency parsing diagram (cần thêm)
- `lstm-architecture.png` - Ảnh LSTM architecture (cần thêm)

## Hướng dẫn sử dụng

### 1. Thêm ảnh của bạn

Thêm các file ảnh sau vào thư mục:

- `profile.jpg` - Ảnh profile của bạn (hình tròn)
- `dependency-parsing.png` - Ảnh dependency parsing (nếu có)
- `lstm-architecture.png` - Ảnh LSTM architecture (nếu có)

### 2. Tùy chỉnh thông tin cá nhân

Mở file `index.html` và chỉnh sửa:

**Tên và thông tin profile:**

- Đổi "Chris Tran" thành tên của bạn
- Cập nhật bio (mô tả về bản thân)
- Thêm links đến Resume, LinkedIn, GitHub của bạn

**Thông tin portfolio:**

- Thêm các projects của bạn
- Cập nhật mô tả các projects
- Thêm links đến GitHub repos

### 3. Tùy chỉnh màu sắc

Mở file `style.css` và chỉnh sửa:

```css
/* Đổi màu chủ đạo (màu xanh) */
.name {
  color: #1e88e5; /* Đổi mã màu này */
}

.links a {
  color: #1e88e5; /* Đổi mã màu này */
}
```

### 4. Chạy website

Mở file `index.html` bằng trình duyệt hoặc sử dụng Live Server trong VS Code.

## Tính năng

✅ Thiết kế responsive (tự động điều chỉnh cho mobile)
✅ Layout 2 cột: Profile bên trái, Portfolio bên phải
✅ Icon GitHub từ Font Awesome
✅ Hover effects cho links
✅ Typography chuyên nghiệp với Google Fonts

## Customization

### Thêm sections mới

Thêm sections mới trong phần portfolio:

```html
<section class="portfolio-section">
  <h2 class="section-title">Tên Section Mới</h2>

  <div class="project">
    <h3 class="project-title">Tên Project</h3>
    <p class="project-description">Mô tả project...</p>
  </div>
</section>
```

### Thêm nhiều projects

Copy và paste phần `<div class="project">` để thêm projects mới.

## Deploy

Bạn có thể deploy website lên:

- **GitHub Pages** (miễn phí)
- **Netlify** (miễn phí)
- **Vercel** (miễn phí)

## Cần hỗ trợ?

Nếu cần thêm tính năng hoặc tùy chỉnh, hãy cho tôi biết!
