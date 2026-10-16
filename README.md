# 🏃‍♂️ CHẠY KHỎI DEADLINE (Escape The Deadline)

> **Game 2D Endless Runner sinh tồn công sở đầy kịch tính!**  
> Chạy trốn con quái vật Deadline khổng lồ, né drama công sở, lách qua sếp và lượm cà phê tăng tốc để sống sót đến cuối kỳ lương!

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-brightgreen?logo=github)](https://dexter140405.github.io/deadline-run/)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-blue?logo=pwa)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![Pure HTML5](https://img.shields.io/badge/HTML5-Canvas%202D-orange?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)

---

## 🎮 Giới Thiệu Trò Chơi

Trong vai một nhân viên văn phòng mẫn cán, bạn đang bị **Con quái vật Deadline** khổng lồ rượt đuổi sát nút sau lưng. Nhiệm vụ của bạn là chạy càng xa càng tốt, nhặt tiền thưởng, nạp cà phê tăng lực và vượt qua muôn vàn kiếp nạn nơi công sở!

### ✨ Các Tính Năng Nổi Bật:
- **Zero Dependencies:** Toàn bộ game chạy thuần bằng **HTML5 Canvas 2D + Web Audio API**, không cần cài thêm thư viện nặng hay Node.js.
- **Hỗ trợ PWA (Progressive Web App):** Có thể bấm **"Cài đặt Ứng dụng" (Install App)** trên Google Chrome / Safari / Edge để chơi như ứng dụng mobile/desktop nguyên bản mà không cần vào trình duyệt.
- **Hệ thống cơ chế công sở độc đáo:**
  - ☕ **Cà phê tăng lực:** Tăng tốc độ và bứt phá khoảng cách với Deadline.
  - 🛡️ **Tấm khiên "Bảo hiểm công việc":** Chống chịu va chạm 1 lần.
  - ⚠️ **Sếp đi tuần:** Phải giữ nút **Cúi (⬇️)** để giả vờ gõ phím cật lực, nếu không sẽ bị phạt!
  - 📱 **Xao nhãng TikTok:** Màn hình rung lắc và bị đảo ngược cụm phím điều khiển.
  - 💥 **Deadline áp sát:** Màn hình chuyển hiệu ứng báo động đỏ và nhịp tim dồn dập.

---

## 🕹️ Hướng Dẫn Điều Khiển

| Thao Tác | Phím Máy Tính | Cảm Ứng Điện Thoại |
|---|---|---|
| **Nhảy / Nhảy đôi (Double Jump)** | Phím `Space` hoặc `Mũi tên Lên (⬆)` / `W` | Chạm vào nửa bên **Phải** màn hình |
| **Cúi / Giả vờ gõ phím khi Sếp tới** | Phím `Mũi tên Xuống (⬇)` hoặc `S` | Chạm và giữ ở nửa bên **Trái** màn hình |
| **Bật / Tắt Âm thanh** | Phím `M` hoặc nút Loa trên màn hình | Bấm icon Loa ở góc phải |
| **Tạm dừng (Pause)** | Phím `P` hoặc `Escape` | Bấm icon Tạm dừng |

---

## 🚀 Triển Khai & Cài Đặt (Deployment)

### 1. Chơi Trực Tiếp Trên Máy Tính (Offline)
Chỉ cần nhấp đúp vào tệp `index.html` trong thư mục là có thể chơi ngay lập tức trên bất kỳ trình duyệt nào (Chrome, Edge, Firefox, Safari).

### 2. Triển Khai Lên GitHub Pages (Miễn phí 100%)
Dự án đã tích hợp sẵn GitHub Actions workflow (`.github/workflows/deploy.yml`):
1. Đẩy code lên GitHub:
   ```bash
   git push -u origin main
   ```
2. Trên GitHub, vào mục **Settings** > **Pages**:
   - Tại mục **Build and deployment** > **Source**: Chọn **GitHub Actions**.
3. Game sẽ tự động được host tại:  
   `https://<username>.github.io/<repository-name>/`

### 3. Cài Đặt Dưới Dạng App (PWA)
- **Trên Điện Thoại (Android / iOS):**
  - Mở link game trên trình duyệt Chrome / Safari.
  - Chọn menu trình duyệt `⋮` hoặc nút Chia sẻ `Share` -> Chọn **"Thêm vào Màn hình chính" (Add to Home Screen)** hoặc **"Cài đặt ứng dụng"**.
- **Trên Máy Tính (Chrome / Edge):**
  - Nhìn vào góc phải thanh địa chỉ (URL bar), bấm vào biểu tượng **"Cài đặt ứng dụng" (Install DeadlineRun)**.

---

## 📁 Cấu Trúc Dự Án

```
Deadline Run/
├── .github/
│   └── workflows/
│       └── deploy.yml      # Tự động deploy lên GitHub Pages
├── .gitignore              # Bỏ qua các file rác OS
├── icon.svg                # Icon ứng dụng & Favicon
├── index.html              # Mã nguồn chính của trò chơi (Canvas + Engine)
├── manifest.json           # Cấu hình PWA để cài đặt ứng dụng
├── README.md               # Tài liệu dự án
└── sw.js                   # Service Worker hỗ trợ chơi offline
```

---

## 📜 Bản Quyền
Dự án được xây dựng phục vụ mục đích giải trí và học tập.
Chúc bạn chạy deadline thành công và không bị sếp tóm! 🎉

