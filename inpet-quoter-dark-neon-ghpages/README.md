# IN PET • Báo giá Pro — Dark Neon (GitHub Pages Ready)

Ứng dụng 1-file (HTML) để tạo/lưu/xuất **báo giá in PET**. Dùng **localStorage** (không cần server).  
Giao diện **Dark Mode + Neon** hiện đại. Hỗ trợ:
- CRUD đơn báo giá, upload nhiều ảnh, xem lại & xuất file cho từng đơn (PNG/PDF).
- Xuất/nhập JSON để backup/khôi phục (bao gồm ảnh dạng dataURL).
- Thống kê tổng hợp (số đơn, tổng tiền, tổng mét, tổng lần in).

## Deploy lên GitHub Pages
1. Tạo repo mới → bật Pages: **Settings → Pages → Source: Deploy from a branch**, Branch: `main`, Folder: `/ (root)`.
2. Tải file **index.html** này vào thư mục gốc của repo.
3. Chờ 30–60s, vào đường link: `https://<tài-khoản>.github.io/<repo>/`.

> Lưu ý: Tính năng **Export PNG/PDF** cần mạng để tải libs từ CDN. Không có mạng vẫn dùng app bình thường (chỉ không xuất được).

## Sao lưu dữ liệu
- Nhấn **Xuất** ở sidebar để tải `inpet-quotes-backup-with-images.json`.
- Khi đổi máy hay clear trình duyệt, dùng **Nhập** để khôi phục.

---

© Phúc Hoàng • IN PET Pro
