# Game Tạo Stress — bản chơi trên điện thoại

Game chạy đường làng Việt Nam đầy bẫy troll. Chạm để nhảy, giữ tay để nhảy cao hơn.

- Web tĩnh (HTML + ảnh WebP), cài được như app (PWA).
- Bảng xếp hạng online dùng Supabase (bảng `stress_scores`).
- Deploy: Vercel, không cần build (thư mục gốc là trang web).

## Hành trình 16 chương
- Chương 1 "Khiêng heo ra chợ" có 10 chặng, sắp đặt bằng chuỗi chữ trong `CHAPTERS` (index.html). Bảng ký tự nằm ngay trên `LV_CHARS`.
- `|` là điểm lưu, `X` là đấu trùm. Sửa chữ là đổi màn.
- Ảnh nền sơ đồ từng chương: `assets/map_ch<n>.webp` (dọc 1080×2400, không có đường, chữ hay số). Chưa có ảnh thì dùng nền màu.

## Điều khiển
- Chạm / phím cách: nhảy (giữ để cao hơn).
- Nút 🩴 / phím J hoặc X: ném dép (chém cọc tre, cành cây; hạ ngỗng, chó, gà). Dép rơi xuống đất, chạy qua để nhặt lại.

