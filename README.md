## How to run

1. Cài đặt Docker
2. Chạy lệnh sau trong thư mục này:

   ```bash
   docker-compose up --build
   ```

3. Truy cập:
   - http://localhost:80 (qua Nginx)
   - http://localhost:8000 (trực tiếp FastAPI)

## Kết quả

- Giao diện trả về JSON đơn giản: `{"message": "Hello from FastAPI!"}`
- Nginx reverse proxy về app thành công.
