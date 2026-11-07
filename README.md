# Hào & Đình — The Wedding Letter

Thiệp cưới điện tử của **Nguyễn Việt Hào & Hồ Vũ Đình** — một trải nghiệm kể chuyện phong cách cinematic với chuyển động cuộn trang, album ảnh và lời mời ngày cưới.

> **Ngày được thiết lập trong mã nguồn:** 20/12/2026, 18:00 (GMT+7). Vui lòng kiểm tra lại toàn bộ thông tin lễ cưới trước khi chia sẻ chính thức.

## Công nghệ

- HTML5, CSS3 và JavaScript thuần (vanilla JS)
- Website tĩnh, không cần Node.js, framework, backend hoặc build
- Phần lớn hình ảnh / tài nguyên và mã nguồn CSS/JS được nhúng trong `index.html`
- Google Fonts là một tài nguyên tải từ bên ngoài
- Triển khai bằng GitHub Pages

## Tính năng

- Thiệp mở đầu tương tác, hiệu ứng cinematic và chuyển cảnh khi cuộn
- Timeline, đếm ngược và lịch ngày cưới
- Thư mời, địa điểm, album ảnh và lời chúc
- Form RSVP, lời chúc (hiện hoạt động dưới dạng **demo trên thiết bị**, chưa gửi về máy chủ)
- Giao diện responsive và tùy chọn giảm chuyển động

## Triển khai GitHub Pages

1. Truy cập https://github.com/new, tạo repository **`hao-dinh-wedding`** và chọn **Public** (nếu dùng GitHub Free).
2. Tải tất cả file từ bộ project này lên **thư mục gốc của repository**: `index.html`, `favicon.svg`, `README.md`, `DEPLOY.md` và `.nojekyll`.
3. Truy cập **Settings → Pages → Build and deployment**.
4. Chọn **Deploy from a branch**, branch **main**, folder **/(root)**, sau đó **Save**.
5. Link website: `https://YOUR_USERNAME.github.io/hao-dinh-wedding/`.

Xem thêm [DEPLOY.md](DEPLOY.md) để biết các bước chi tiết.

## Cấu trúc dự án

```text
hao-dinh-wedding/
├── index.html       # Toàn bộ website và tài nguyên nhúng
├── favicon.svg      # Biểu tượng trên tab trình duyệt
├── README.md         # Tổng quan dự án
├── DEPLOY.md         # Hướng dẫn deploy, cập nhật
└── .nojekyll         # Không chạy quá trình Jekyll
```

## Lưu ý trước khi dùng thật

- **RSVP và lời chúc không được gửi đến chủ thiệp.** Form hiện chỉ lưu vào `localStorage` trên chính trình duyệt người truy cập. Nếu cần nhận câu trả lời của khách mời, phải tích hợp backend hoặc dịch vụ lưu trữ dữ liệu (Google Sheets, Firebase, Supabase, v.v.).
- **Địa điểm và lịch:** Trong mã nguồn hiện có địa chỉ **The Reverie Saigon** và phần mô tả lịch ghi **demo**. Xác nhận/đổi thông tin này trước khi phát hành.
- **Quyền riêng tư:** Repository Public và website GitHub Pages đều có thể được truy cập công khai; kiểm tra kỹ ảnh, thông tin gia đình, thời gian và địa điểm trước khi chia sẻ.
- **Ảnh đại diện khi gửi link:** Chưa cấu hình `og:image` có URL tuyệt đối. Khi đã biết địa chỉ GitHub Pages chính thức, có thể bổ sung ảnh thumbnail để hiển thị đẹp trên mạng xã hội.

## Cập nhật website

Chỉnh sửa `index.html` và commit lên nhánh `main`. GitHub Pages sẽ tự xuất bản phiên bản mới.

---

**Project:** Hào & Đình — The Wedding Letter  
**Repository:** `hao-dinh-wedding`  
**Stack:** HTML / CSS / JavaScript  
**License:** Chưa cấp giấy phép tái sử dụng. Các hình ảnh, tư liệu và nội dung trong thiệp không mặc nhiên được phép sao chép.
