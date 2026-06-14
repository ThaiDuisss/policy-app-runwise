# Running App Legal Pages

Bộ trang tĩnh để triển khai bằng GitHub Pages.

## Các file

- `index.html`: Trang chủ
- `privacy-policy.html`: Chính sách quyền riêng tư
- `terms-of-service.html`: Điều khoản sử dụng
- `account-deletion.html`: Yêu cầu xóa tài khoản
- `styles.css`: Giao diện chung

## Việc cần sửa trước khi phát hành

1. Thay toàn bộ `Running App` bằng tên ứng dụng chính thức.
2. Kiểm tra email hỗ trợ `thai110504@gmail.com`.
3. Xóa hoặc chỉnh các phần liên quan đến SDK/tính năng mà ứng dụng không thực sự sử dụng.
4. Nếu có backend xử lý yêu cầu xóa tài khoản, thay form `mailto:` bằng API hoặc form thật.
5. Đảm bảo nội dung trang khớp với biểu mẫu Data safety trên Google Play Console.

## Đưa lên GitHub Pages

1. Tạo repository public, ví dụ `running-app-legal`.
2. Upload toàn bộ file trong thư mục này vào branch `main`.
3. Vào `Settings` → `Pages`.
4. Chọn `Deploy from a branch`.
5. Chọn branch `main`, thư mục `/root`, rồi nhấn `Save`.

Sau khi xuất bản, các URL sẽ có dạng:

- `https://<username>.github.io/running-app-legal/privacy-policy.html`
- `https://<username>.github.io/running-app-legal/terms-of-service.html`
- `https://<username>.github.io/running-app-legal/account-deletion.html`
