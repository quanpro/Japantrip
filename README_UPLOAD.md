# Japantrip · GitHub Pages local assets

## Cấu trúc cần giữ

- `index.html`
- `assets/images/...`

## Cách cập nhật lên GitHub Pages

1. Giải nén gói zip này.
2. Vào repo `Japantrip` trên GitHub.
3. Upload **toàn bộ nội dung** trong thư mục này, đặc biệt là `index.html` và thư mục `assets`.
4. Nếu GitHub hỏi ghi đè, chọn thay file cũ.
5. Commit changes.
6. Chờ 1–2 phút rồi refresh lại link GitHub Pages.

## Vì sao bản này ổn định hơn

Ảnh đã được tải về local trong `assets/images`, nên website không còn phụ thuộc ảnh ngoài. Khi GitHub Pages tải trang, ảnh sẽ lấy trực tiếp từ repo của bạn.

## Nếu muốn sửa nội dung

- Mở `index.html` bằng VS Code hoặc bất kỳ editor nào.
- Không đổi tên thư mục `assets`.
- Nếu thay ảnh, giữ đúng tên file hoặc sửa lại đường dẫn trong HTML.
