---
title: Hướng dẫn sử dụng VClip
description: Phím tắt, ghim, tìm kiếm, ảnh, cài đặt, quyền, dung lượng, gỡ cài đặt và xử lý sự cố của VClip trên macOS.
---

# Hướng dẫn sử dụng VClip

[← Trang chủ](./) · [Tải về](https://github.com/phuongvudev/VClip/releases/latest)

VClip nhớ mọi thứ bạn copy trên Mac (text, link, ảnh, file). Nhấn **⌘⇧V** ở bất kỳ app nào để mở lại và dán.

## Mục lục

- [Bắt đầu](#bắt-đầu)
- [Phím tắt](#phím-tắt)
- [Panel bộ nhớ tạm](#panel-bộ-nhớ-tạm)
- [Cài đặt](#cài-đặt)
- [Quyền cần cấp](#quyền-cần-cấp)
- [Dung lượng và dữ liệu](#dung-lượng-và-dữ-liệu)
- [Cập nhật và gỡ cài đặt](#cập-nhật-và-gỡ-cài-đặt)
- [Xử lý sự cố](#xử-lý-sự-cố)

## Bắt đầu

1. Cài file `VClip-<phiên bản>.pkg`. VClip tự mở, biểu tượng nằm trên thanh menu.
2. Cấp quyền **Accessibility** khi được hỏi (xem [Quyền cần cấp](#quyền-cần-cấp)).
3. Copy vài thứ như bình thường (⌘C, chuột phải → Copy, chụp màn hình vào clipboard…).
4. Đặt con trỏ vào chỗ muốn dán, nhấn **⌘⇧V**, click một thẻ. Xong.

## Phím tắt

| Phím | Tác dụng |
|---|---|
| `⌘⇧V` | Mở / đóng bộ nhớ tạm (đổi được trong Cài đặt → Chung) |
| Click hoặc `↩` | Dán mục đang chọn |
| `⌥↩` | Dán dạng plain text (bỏ định dạng chữ đậm, màu, cỡ chữ) |
| `⌘1` … `⌘9` | Dán nhanh mục thứ 1–9 (số hiện ở góc mỗi thẻ) |
| `← ↑ ↓ →` | Di chuyển giữa các thẻ |
| `Space` | Xem ảnh lớn (khi ô tìm kiếm đang trống) |
| `⌘P` | Ghim / bỏ ghim mục đang chọn |
| `⌘⌫` | Xoá mục đang chọn |
| `⌘,` | Mở Cài đặt |
| `Esc` | Đóng ảnh lớn, rồi đóng panel |

## Panel bộ nhớ tạm

- **Vị trí:** mặc định hiện ngay dưới con trỏ nhập liệu. Sát đáy màn hình thì lật lên trên. Một số app không cho biết vị trí con trỏ (Terminal, app Java, game), khi đó panel hiện tại vị trí chuột. Đổi trong Cài đặt → Giao diện.
- **Thẻ:** text hiện tối đa vài dòng đầu, link màu xanh, ảnh hiện thumbnail, file hiện icon và tên. Text copy từ Terminal, iTerm, Ghostty, Warp, VS Code, Xcode hiện font monospace. Góc dưới mỗi thẻ có icon app nguồn và thời gian copy.
- **Ghim 📌:** rê chuột vào thẻ, bấm nút ghim. Mục đã ghim luôn nằm đầu, không bao giờ bị xoá tự động. Nút 📌 trên header để chỉ xem mục đã ghim.
- **Xoá:** nút ✕ trên thẻ xoá một mục. Nút 🗑 trên header xoá tất cả mục chưa ghim (bấm 2 lần để xác nhận).
- **Tìm kiếm:** gõ ngay khi panel mở. Tìm trong 5.000 ký tự đầu của mỗi mục và tên file.
- **Chuột phải vào thẻ:** dán, dán plain text, xem ảnh, mở link, hiện file trong Finder, ghim, xoá.
- **Copy thêm khi panel đang mở:** mục mới tự hiện lên đầu.

## Cài đặt

Mở bằng nút ⚙️ trên panel, `⌘,`, hoặc menu VClip → **Cài đặt…**

**Chung**
- Phím tắt mở bộ nhớ tạm, mở cùng macOS.
- **Tự động dán:** tắt đi thì chọn mục chỉ đưa vào clipboard, bạn tự nhấn ⌘V.
- **Luôn dán dạng plain text.**
- **Ghi lại:** chọn loại muốn lưu: text và link, ảnh, file.
- **Không ghi lại từ các app:** thêm app (từ danh sách đang chạy hoặc thư mục Applications). Trình quản lý mật khẩu luôn bị bỏ qua.

**Giao diện**
- Vị trí panel: dưới con trỏ nhập liệu, tại chuột, giữa màn hình.
- Số cột: 2, 3 hoặc 4.
- Hiện phím tắt ⌘1–9, hiện icon app nguồn.

**Lưu trữ**
- Giữ text, link, file: 1 giờ → mãi mãi (mặc định 30 ngày).
- Giữ ảnh: riêng, mặc định 7 ngày, hoặc "Giống text".
- Số mục tối đa (mặc định 500), dung lượng tối đa (mặc định 500 MB), bỏ qua ảnh lớn hơn (mặc định 20 MB).
- **Nén ảnh (HEIC):** ảnh nhỏ hơn 5–10 lần, đổi lại bị nén nhẹ. Ảnh nền trong suốt vẫn giữ PNG.
- Xem dung lượng đang dùng, **Xoá ảnh…**, **Mở thư mục dữ liệu**.

**Nâng cao**
- Nghe ⌘C / ⌘X để ghi ngay, chu kỳ kiểm tra clipboard khi rảnh (1, 2, 5 giây).
- Số mục mỗi lần tải, kích thước thumbnail, bỏ qua text lớn hơn.
- **Độ trễ trước khi dán:** tăng lên nếu dán vào app Electron hoặc Java bị trượt.
- Khôi phục mặc định.

## Quyền cần cấp

**Accessibility** (System Settings → Privacy & Security → Accessibility → bật VClip) dùng để:
- tự nhấn ⌘V giúp bạn sau khi chọn mục;
- biết con trỏ nhập liệu đang ở đâu để hiện panel ngay bên dưới;
- nghe phím ⌘C / ⌘X để ghi lại tức thì.

Không cấp quyền thì VClip vẫn lưu lịch sử. Chọn mục rồi tự nhấn ⌘V.

Trên macOS 15.4 trở lên, nếu macOS hỏi VClip có được **đọc clipboard** không, hãy chọn **Always Allow**. Xem trạng thái trong Cài đặt → Chung → Quyền.

## Dung lượng và dữ liệu

- Dữ liệu chỉ nằm trên máy bạn, trong `~/Library/Application Support/VClip`. VClip không có tài khoản và không gửi gì lên mạng.
- **Ảnh copy từ Finder** (copy file ảnh) chỉ lưu đường dẫn và một thumbnail nhỏ. File bị đổi tên hay di chuyển vẫn tìm lại được; file bị xoá thì thẻ hiện "File không còn".
- **Ảnh không có file** (chụp màn hình vào clipboard, "Copy Image" từ trình duyệt, Figma…) phải lưu lại, nên bị giới hạn bởi thời gian lưu ảnh và dung lượng tối đa. Vượt mức thì VClip xoá mục cũ nhất chưa ghim, ưu tiên ảnh.
- Không lưu: nội dung đánh dấu là mật khẩu, mọi thứ từ trình quản lý mật khẩu và app trong danh sách bỏ qua, text lớn hơn ngưỡng, ảnh lớn hơn ngưỡng.

## Cập nhật và gỡ cài đặt

**Cập nhật:** tải file `.pkg` mới rồi cài đè. Lịch sử, mục đã ghim và cài đặt được giữ nguyên.

**Gỡ cài đặt:** menu VClip → **Gỡ cài đặt VClip…** (hoặc Cài đặt → Chung → cuối trang), rồi chọn:
- **Gỡ cài đặt:** gỡ app, giữ lịch sử và cài đặt để cài lại dùng tiếp.
- **Gỡ sạch:** gỡ app và xoá luôn lịch sử (kể cả ảnh) và cài đặt.

VClip cũng tự bỏ khỏi Login Items và thu hồi quyền Accessibility.

## Xử lý sự cố

| Hiện tượng | Cách xử lý |
|---|---|
| Nhấn ⌘⇧V không thấy gì | Kiểm tra biểu tượng VClip có trên thanh menu. App khác có thể đang dùng ⌘⇧V: đổi phím trong Cài đặt → Chung |
| Chọn mục nhưng không tự dán | Cấp quyền Accessibility. Nếu đã bật mà vẫn không được: xoá VClip khỏi danh sách (−) rồi thêm lại |
| Dán bị trượt / dán nhầm chỗ ở một số app | Cài đặt → Nâng cao → tăng **Độ trễ trước khi dán** |
| Panel không hiện dưới con trỏ | App đó không cho biết vị trí con trỏ. Panel sẽ hiện tại chuột |
| Có thứ copy không được ghi lại | Kiểm tra **Tạm dừng ghi** trên menu, loại nội dung trong Cài đặt → Chung, và danh sách app bỏ qua |
| Tốn nhiều dung lượng | Cài đặt → Lưu trữ: giảm thời gian giữ ảnh, giảm dung lượng tối đa, bật nén HEIC, hoặc **Xoá ảnh…** |
