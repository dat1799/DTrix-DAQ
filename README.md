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

## ⚖️ Miễn trừ trách nhiệm (Disclaimer)

- Phần mềm này được cung cấp theo nguyên trạng (**"AS IS"**) cho mục đích nghiên cứu, học tập và tự động hóa cá nhân; không có bất kỳ cam kết hay bảo đảm nào về tính ổn định liên tục trước các thay đổi từ phía Discord.
- **Không liên kết chính thức**: **DTrix Discord Auto Quests (DTrix-DAQ)** là công cụ độc lập, không thuộc, không được tài trợ hay xác nhận bởi **Discord Inc.**
- **Rủi ro Điều khoản dịch vụ (ToS)**: Việc sử dụng công cụ tự động hóa bằng tài khoản người dùng có thể vi phạm [Discord Terms of Service](https://discord.com/terms). Các tính năng Safe Mode / Stealth / chống quét chỉ giúp giảm dấu hiệu bất thường, **không đảm bảo 100% tránh bị giới hạn tính năng, tạm khóa hoặc khóa vĩnh viễn tài khoản**.
- **Trách nhiệm người dùng**: Người dùng tự chịu toàn bộ rủi ro khi tải về, nhập token/quét QR, sử dụng proxy và vận hành phần mềm. Tác giả và bên phân phối không chịu trách nhiệm đối với bất kỳ tổn thất dữ liệu, khóa tài khoản hay thiệt hại trực tiếp/gián tiếp nào phát sinh.
- **Bảo mật dữ liệu**: Hãy bật **Safe Mode**, dùng **Proxy** riêng nếu chạy nhiều tài khoản và tuyệt đối không chia sẻ token, proxy credentials hoặc file `vault.json` cho người khác.

