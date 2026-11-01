# Dudinh Nhat — GitHub Pages

Website cá nhân tĩnh, xây dựng bằng HTML, CSS và JavaScript thuần. Không cần framework, Node.js hay bước build.

## Tạo repository

1. Đăng nhập GitHub với tài khoản `dinhnhat7993`.
2. Tạo repository mới, đặt tên chính xác `dinhnhat7993.github.io`.
3. Chọn **Public**. Có thể để repository trống, không tạo README, license hoặc `.gitignore` trên GitHub vì các file này đã có trong dự án.

## Push code lên GitHub

Mở terminal tại thư mục dự án, sau đó chạy:

```bash
git init
git add .
git commit -m "Initial GitHub Pages site"
git branch -M main
git remote add origin https://github.com/dinhnhat7993/dinhnhat7993.github.io.git
git push -u origin main
```

## Bật GitHub Pages

Trong repository, mở **Settings → Pages**. Tại **Build and deployment**, chọn **Deploy from a branch**, chọn branch **main** và thư mục **/ (root)**, rồi lưu lại.

## Kiểm tra website

Truy cập [https://dinhnhat7993.github.io](https://dinhnhat7993.github.io). Sau khi push hoặc thay đổi cấu hình Pages, website có thể mất vài phút để cập nhật.

Email trên trang hiện là địa chỉ placeholder `your-email@example.com`; hãy thay bằng email muốn công khai trước khi sử dụng.
