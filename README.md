# ping-dist

Nơi đặt bản cài và appcast cho **[Ping](https://github.com/hnaht95/ping)** — app macOS
nằm trên menu bar, nhắc sinh nhật, ghi chú theo ngày và nhắc uống nước.

Repo này công khai vì app cần một địa chỉ ai cũng tải được để tự cập nhật.
Mã nguồn nằm ở repo `ping` (riêng tư).

- `appcast.xml` — feed cho Sparkle, ký bằng khoá EdDSA
- Bản cài đính kèm ở phần **Releases**

## Tải về

Vào [Releases](https://github.com/hnaht95/ping-dist/releases), tải file `.zip` mới nhất,
nhấn đúp trong Finder để giải nén, kéo **Ping.app** vào thư mục `Applications`.

App đã ký Developer ID và qua kiểm duyệt của Apple nên không cần chạy lệnh Terminal nào.
Yêu cầu macOS 12 trở lên, máy Intel hoặc Apple Silicon.
