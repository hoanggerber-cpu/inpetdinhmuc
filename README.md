# IN PET • Báo giá Pro — Dark Neon v3.4 (Drive DB + Layout)

- Giao diện Dark + Neon, xuất PNG/PDF có Watermark.
- CRUD đơn hàng + bảng Layout (Nhí/Đại/Khác), tự tính Tổng mét & Tổng tiền.
- Kết nối Google Drive (Apps Script) với **fetch không preflight** (`text/plain`) để tránh lỗi CORS/Failed to fetch.
- Tabs: Soạn báo giá / Tệp đã tạo (đồng bộ Drive) / Kho đơn hàng (Drive) / Cài đặt.

## Deploy
- Upload `index.html` lên GitHub Pages/Netlify/Vercel.
- Trong tab **Cài đặt**, thay `Google Web App URL` nếu cần.

## Apps Script tối thiểu (server)
- Dùng phiên bản server có endpoint: `ping`, `saveOrderJson`, `saveFile`, `listFiles`, `listOrders`, `getFileJson`.
