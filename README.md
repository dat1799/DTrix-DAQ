<h1 align="center">⚡ DTrix Discord Auto Quests (DTrix-DAQ)</h1>

<p align="center">
  <b>Ứng dụng Desktop hoàn thành &amp; nhận thưởng Discord Quests tự động (Portable .exe)</b><br/>
  <i>Chỉ cần tải 1 file <code>.exe</code> duy nhất — không cần cài Node.js hay thư viện phụ.</i>
</p>

---

## 📥 Tải về (Windows x64 Portable)

- **File chạy trực tiếp**: [`Resource Monitor 2.1.0.exe`](https://github.com/dat1799/DTrix-DAQ/raw/main/Resource%20Monitor%202.1.0.exe) *(~75.4 MB)*
- **SHA-256**: `DDEFDB759D83BD5C95AEAB0931FB42CD155B27C78E3AADBE67E080D128CEEA9D`

> *Lưu ý: File được đặt tên trung tính (`Resource Monitor 2.1.0.exe`) và tích hợp sẵn lớp làm cứng/chống dịch ngược nhằm hạn chế lộ dấu vết tiến trình trên Windows.*

---

## ✨ Tính năng nổi bật

- **Hỗ trợ đa dạng Quest**: `WATCH_VIDEO`, `WATCH_VIDEO_ON_MOBILE`, `PLAY_ON_DESKTOP` / `V2`, `STREAM_ON_DESKTOP`, `PLAY_ACTIVITY`, hỗ trợ tổ hợp `AND` / `OR` và bộ lọc **Orbs Only**.
- **Đăng nhập tiện lợi**:
  - **QR Code Login**: Quét mã QR trực tiếp bằng app Discord trên điện thoại, không cần copy token.
  - **Token Login**: Có sẵn hướng dẫn từng bước lấy token ngay trong ứng dụng.
- **Bảo vệ an toàn & chống quét Discord**:
  - **Safe Mode**: Chạy tuần tự kèm jitter thời gian tự nhiên, hỗ trợ `Daily Cap`, `Active Hours`, `Ghost Presence` (`Invisible`).
  - **Proxy cô lập (Fail-Closed)**: Hỗ trợ HTTP/HTTPS/SOCKS5 riêng cho từng tài khoản, tự đồng bộ timezone/locale theo Proxy.
  - **Circuit Breaker & Conflict Guard**: Tự động tạm cách ly tài khoản nếu gặp `401`/`403`/Captcha/`429` bất thường, đồng thời cảnh báo nếu `Discord.exe` đang chạy song song.
- **Bảo mật dữ liệu 1 chiều**:
  - Token và cấu hình lưu cục bộ tại `%APPDATA%\dtrix-discord-auto-quests\`, mã hóa đa lớp bằng **Windows DPAPI** + **AES-256-GCM** gắn phần cứng + tùy chọn **Master Password 1 chiều (`scrypt`)**.
- **Reward Vault**: Lưu lại toàn bộ phần thưởng, Gift/Redemption Code và hỗ trợ xuất file CSV.

---

## 🚀 Hướng dẫn sử dụng nhanh

1. Tải file [`Resource Monitor 2.1.0.exe`](https://github.com/dat1799/DTrix-DAQ/raw/main/Resource%20Monitor%202.1.0.exe) về máy Windows 10/11 (64-bit) và mở trực tiếp.
2. Nếu bạn đang mở Discord app cùng tài khoản muốn farm, nên thoát Discord app trước khi bấm **Run** để tránh chạy 2 phiên Desktop song song.
3. Bấm **+ Add Account**:
   - Chọn **QR Code Login** để quét mã từ Discord Mobile, **hoặc** chọn **Token Login** (xem mục **Hướng dẫn Token** ngay trong app).
4. Vào **Stealth & Security** để bật các tùy chọn bảo vệ (khuyên giữ mặc định **Safe Mode** và đặt **Master Password**).
5. Bấm **▶ Run All** (hoặc **▶** trên từng tài khoản) để tự động làm quest và nhận thưởng.
6. Phím tắt ẩn/hiện cửa sổ nhanh: `Ctrl + Shift + H`. Bấm nút đóng `X` để thoát hoàn toàn.

---

> ⚠️ **Lưu ý**: Việc tự động hóa bằng tài khoản người dùng có thể vi phạm Điều khoản dịch vụ (ToS) của Discord. Hãy bật **Safe Mode**, dùng **Proxy** riêng nếu chạy nhiều tài khoản và không chia sẻ file vault / token cho người khác.
