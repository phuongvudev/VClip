# VClip

Bộ nhớ tạm (clipboard history) cho macOS, giống **Win + V** trên Windows: nhấn **⌥⌘V** để mở lại mọi thứ bạn đã copy và dán ngay.

🌐 **Trang chủ:** https://phuongvudev.github.io/VClip/ · ⬇ **Tải về:** [bản mới nhất](https://github.com/phuongvudev/VClip/releases/latest)

*VClip is a free clipboard history manager for macOS. Press ⌥⌘V to bring back anything you copied (text, links, images, files) right under your text cursor, and paste it with one click.*

## Tính năng

- **Hiện ngay dưới chỗ đang gõ:** panel bật lên dưới con trỏ nhập liệu, không cướp focus của app đang dùng. Chọn một thẻ là dán luôn.
- **Lưới thẻ xem nhanh:** text, link, ảnh (có thumbnail), file. Nhấn **Space** để xem ảnh lớn.
- **Ghim** mục hay dùng lên đầu, **xoá** từng mục hoặc xoá tất cả (giữ mục đã ghim).
- **Tìm kiếm** trong toàn bộ lịch sử, cuộn vô hạn.
- **Gọn nhẹ:** gần như không tốn CPU khi rảnh, tự dọn mục cũ, giới hạn dung lượng. Ảnh copy từ Finder chỉ lưu đường dẫn.
- **Riêng tư:** không ghi lại mật khẩu và nội dung từ trình quản lý mật khẩu, dữ liệu chỉ nằm trên máy bạn.
- **Cài bằng file `.pkg`, gỡ ngay từ menu.**

## Cài đặt

Yêu cầu macOS 14 trở lên, chạy được trên cả Apple Silicon lẫn Intel.

1. Tải file **`VClip-<phiên bản>.pkg`** ở trang [**Releases**](https://github.com/phuongvudev/VClip/releases/latest).
2. Bấm đúp vào file, chọn **Continue** rồi **Install**, sau đó nhập mật khẩu máy. VClip tự mở sau khi cài, biểu tượng nằm trên thanh menu.
3. Khi được hỏi, cấp quyền **Accessibility** cho VClip (**System Settings → Privacy & Security → Accessibility**). Quyền này để VClip tự dán và hiện panel ngay dưới chỗ đang gõ.

### Dùng thử

| Phím | Tác dụng |
|---|---|
| `⌥⌘V` | Mở / đóng bộ nhớ tạm (đổi được trong Cài đặt) |
| Click, `↩` | Dán mục đang chọn |
| `⌥↩` | Dán dạng plain text |
| `⌘1` … `⌘9` | Dán nhanh mục thứ 1–9 |
| `← ↑ ↓ →` | Chọn thẻ |
| `Space` | Xem ảnh lớn |
| `⌘P` / `⌘⌫` | Ghim / xoá mục đang chọn |
| `⌘,` | Mở Cài đặt |
| `Esc` | Đóng |

Trong **Cài đặt** bạn chỉnh được vị trí panel, số cột, thời gian lưu, dung lượng tối đa, app không muốn ghi lại, và nhiều tuỳ chọn khác. Xem đầy đủ trong [**Hướng dẫn sử dụng**](docs/HUONG_DAN_SU_DUNG.md).

### Cập nhật

Tải file `.pkg` mới rồi cài đè lên bản cũ. Lịch sử clipboard và cài đặt được giữ nguyên.

### Gỡ cài đặt

Bấm biểu tượng VClip trên thanh menu, chọn **Gỡ cài đặt VClip…**, rồi chọn một trong hai:
- **Gỡ cài đặt:** gỡ app, giữ lại lịch sử clipboard và cài đặt.
- **Gỡ sạch:** gỡ app và xoá luôn lịch sử clipboard (kể cả ảnh) và cài đặt.

## Về repo này

Repo này chứa trang chủ (`docs/`, GitHub Pages) và các bản phát hành trong [Releases](https://github.com/phuongvudev/VClip/releases). Báo lỗi hoặc góp ý ở [Issues](https://github.com/phuongvudev/VClip/issues).

© 2026 Vũ Phương. VClip miễn phí cho mọi người.
