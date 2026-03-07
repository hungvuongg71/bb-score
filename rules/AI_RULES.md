# AI Project Rules: Basketball Scoreboard (BBS)

## 1. Core Tech Stack

- **Single File Architecture:** Tất cả HTML, CSS, và JavaScript phải nằm trong duy nhất file `index.html`.
- **Vanilla Only:** Không sử dụng thư viện ngoài (No React, No jQuery, No Bootstrap) để đảm bảo tốc độ tải tối đa.

## 2. Design Principles

- **Theme:** Dark Mode chủ đạo (Background: #000).
- **Typography:** Sử dụng font dạng Digital/Segment (hoặc Monospace làm fallback) để mô phỏng bảng điện tử LED.
- **Responsiveness:** - Layout phải tự động chuyển đổi giữa dọc (Portrait) và ngang (Landscape).
  - Sử dụng Flexbox/Grid và đơn vị `vh`/`vw` để bảng điểm luôn full màn hình.

## 3. Basketball Logic Rules

- **Scoring:** Hỗ trợ các nút +1 (Free Throw), +2 (Field Goal), +3 (Three-pointer).
- **Validation:** Không cho phép điểm số âm.
- **Persistence:** Lưu tên đội và điểm số vào `localStorage` để tránh mất dữ liệu khi lỡ tay load lại trang.

## 4. Code Standards

- Biến số phải rõ ràng (ví dụ: `homeScore`, `awayScore`).
- Comment đầy đủ các hàm xử lý sự kiện (Event Handlers).
