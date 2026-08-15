# AdBlock VN — Bản 2

Ứng dụng Android chặn quảng cáo/tracker cấp thiết bị bằng `VpnService` + DNS.

## Tính năng
- Bật/tắt chặn quảng cáo.
- Chạy không cần root.
- Thống kê số truy vấn bị chặn.
- Hiển thị danh sách domain chặn mặc định.
- Android 8.0+ (API 26+).

## Build APK trên điện thoại bằng GitHub Actions
1. Tạo repository GitHub mới.
2. Upload toàn bộ nội dung thư mục `AdBlockVN` lên repository.
3. Vào **Actions** → **Build AdBlock VN APK** → **Run workflow**.
4. Khi chạy xong, mở workflow → phần **Artifacts** → tải `AdBlockVN-debug-apk`.
5. Giải nén artifact và cài `app-debug.apk` trên Android.

## Lưu ý
Bản này lọc DNS với danh sách domain mặc định. Một số quảng cáo dùng HTTPS/DoH hoặc phân phối cùng domain nội dung có thể không bị chặn.
