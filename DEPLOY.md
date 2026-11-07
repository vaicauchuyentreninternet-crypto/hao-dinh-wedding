# Hướng dẫn xuất bản thiệp cưới Hào & Đình lên GitHub Pages

## A. Thông tin để tạo Repository

- **Repository name:** `hao-dinh-wedding`
- **Description:** `A cinematic wedding invitation for Hào & Đình — memories, love and a beautiful day.`
- **Visibility:** `Public` (dùng GitHub Free để bật Pages dễ nhất)
- **Initialize repository:** không bắt buộc thêm README/.gitignore/license vì bộ project đã có README
- **Topics:** `wedding-invitation`, `wedding-website`, `github-pages`, `html`, `css`, `javascript`, `cinematic-design`
- **Commit message:** `feat: publish Hao & Dinh wedding invitation`

## B. Tải file lên

1. Truy cập https://github.com/new rồi tạo repository với các thông tin ở trên.
2. Vào repository → **Add file → Upload files**.
3. Nếu dùng file ZIP: **giải nén** rồi upload **từng file bên trong**, KHÔNG upload nguyên file `.zip`.
4. Đảm bảo **`index.html` nằm ngay thư mục gốc** (không để trong thư mục con).
5. Nhấn **Commit changes**.

## C. Bật GitHub Pages

1. Chọn **Settings → Pages**.
2. Mục **Build and deployment → Source**: chọn **Deploy from a branch**.
3. Branch: **main**; Folder: **/(root)**.
4. Nhấn **Save**.
5. Sau khi xuất bản, dùng **Visit site** để mở website, hoặc mở `https://YOUR_USERNAME.github.io/hao-dinh-wedding/`.

## D. Kiểm thử sau khi xuất bản

- Mở link trên cả điện thoại và máy tính.
- Thử mở thiệp, cuộn qua tất cả chương, xem ảnh và thử phần âm thanh.
- Xác nhận ngày 20/12/2026 và giờ 18:00 đã chính xác.
- Xác nhận địa chỉ, hướng dẫn đường đi và lịch tải xuống (đang có nội dung demo).
- Chỉ gửi RSVP cho khách khi đã tích hợp lưu dữ liệu về hệ thống (hiện là lưu cục bộ trên trình duyệt).

## E. Thay đổi sau này

Trên GitHub, mở `index.html` → Edit (biểu tượng bút chì) → sửa → **Commit changes**. Trang sẽ tự cập nhật sau khi GitHub Pages triển khai lại.

### Lưu ý

Trang GitHub Pages là **website công khai**. Không thêm mật khẩu, API key bí mật, dữ liệu khách mời chưa được phép công khai hay các tập tin riêng tư vào repository.
