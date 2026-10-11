# BT34 - Flexbox

Repo gồm 2 bài thực hành Flexbox:

## 1. Căn giữa phần tử hoàn hảo

Sử dụng 3 thuộc tính chính:

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

Mỗi thẻ dùng `flex: 1 1 calc(25% - 20px)` và `min-width: 220px` để tự động co giãn và xuống dòng khi màn hình nhỏ hơn.

## Cách chạy

Mở file `index.html` bằng trình duyệt hoặc Live Server trong VS Code.
