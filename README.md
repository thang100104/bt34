# BT34 - Flexbox

Repo gồm 3 bài thực hành Flexbox:

## 1. Căn giữa phần tử hoàn hảo

Sử dụng:

```css
display: flex;
justify-content: center;
align-items: center;
```

## 2. Sắp xếp danh sách thẻ sản phẩm co giãn linh hoạt

Danh sách gồm 4 thẻ sản phẩm, sử dụng:

```css
display: flex;
flex-wrap: wrap;
gap: 20px;
```

Mỗi thẻ sử dụng `flex` và `min-width` để tự động co giãn và xuống dòng.

## 3. Mini project: Thư viện ảnh đáp ứng bằng Flexbox

File: `gallery.html`

Thư viện gồm 10 ảnh và sử dụng:

```css
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 16px;
```

Mỗi ảnh dùng:

```css
flex: 1 1 300px;
```

Ảnh được đặt `width: 100%`, `height: 100%` và `object-fit: cover` để luôn vừa khung mà không bị méo.

Có thêm hiệu ứng hover với `transform: scale(1.03)`.

## Cách chạy

- Mở `index.html` để xem các bài Flexbox trước.
- Mở `gallery.html` để xem bài thư viện ảnh.
