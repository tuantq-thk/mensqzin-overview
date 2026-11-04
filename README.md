# MensQzin project overview

Bộ tài liệu HTML tĩnh để đọc nhanh kiến trúc repository FuelPHP, các entry point, runtime configuration và HTTP request workflow.

## Mở tài liệu

Mở [index.html](./index.html) để xem trang tổng quan và 6 bài tài liệu:

- [Bản đồ thư mục repository](./fuel-directory-map.html)
- [Tổng quan repository FuelPHP](./fuel-repository-overview.html)
- [Cấu hình runtime Fuel](./fuel-runtime-configuration.html)
- [Luồng HTTP request](./fuel-http-request-workflow.html)
- [Kiến trúc ứng dụng từ source](./fuel-source-architecture.html)
- [Các entry point của repository](./fuel-entrypoints.html)

## Chạy local

Có thể mở trực tiếp `index.html`. Nếu trình duyệt hạn chế một số tính năng khi mở bằng `file://`, chạy web server tĩnh:

```bash
python3 -m http.server 8000
```

Sau đó truy cập <http://localhost:8000/>.

Các diagram là file HTML độc lập, không cần build step hay dependency cài thêm.
