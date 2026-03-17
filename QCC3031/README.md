# QCC3031 ADK – Sink Application

Firmware dựa trên Qualcomm ADK cho chipset **QCC3031** — ứng dụng sink (loa Bluetooth với TWS, A2DP/AVRCP và wired audio).

---

## Nút bấm (PIO)

| Chức năng | PIO | Hành động |
|---|---:|---|
| Nguồn | PIO&nbsp;0 | Nhấn giữ lâu: Bật/tắt nguồn. Nhấn giữ rất lâu: Vào chế độ ghép nối Bluetooth. |
| Giảm âm lượng | PIO&nbsp;2 | Nhấn lặp: Giảm âm lượng. Nhấn 1 lần: Bài trước (khi đang phát nhạc). |
| Tăng âm lượng | PIO&nbsp;3 | Nhấn lặp: Tăng âm lượng. Nhấn 1 lần: Bài tiếp theo (khi đang phát nhạc). |
| Play / Pause | PIO&nbsp;4 | Nhấn 1 lần: Phát/Tạm dừng. Nhấn giữ rất lâu: Vào chế độ ghép nối Bluetooth. Nhấn giữ cực lâu: Xóa danh sách thiết bị đã ghép nối. |
| TWS | PIO&nbsp;5 | Nhấn 1 lần: Ghép nối 2 loa TWS. Nhấn giữ lâu: Ngắt kết nối TWS. |


---

## AUX

- PIO&nbsp;23:
	- `Tín hiệu xuống` = phát hiện kết nối AUX (AUX detected).
	- `Tín hiệu lên` = phát hiện ngắt kết nối AUX (AUX removed).

---

## Crossover

- PIO&nbsp;22:
	- `High` — Kích hoạt phân tần chủ động ở chế độ mono. Tần số cắt = 3 kHz, kênh trái xử lý Bass, kênh phải xử lý Treble.
	- `Low` — Trở về chế độ stereo bình thường.

Lưu ý: Chỉ thay đổi chế độ sau khi thiết bị khởi động.

---

## Mute

- PIO&nbsp;21:
  - `Power on` = High
  - `Power off` = Low

- PIO&nbsp;20:
  - `Play` = High
  - `Pause` = Low

---

## Phiên bản và Ghi chú phát hành

- Phiên bản hiện tại: v1.1
- Tính năng sắp tới: auto bassboost (đang phát triển).

---

## Liên hệ / Báo lỗi

- Vui lòng mở issue hoặc liên hệ người chịu trách nhiệm firmware trên kho mã nguồn nội bộ.

---
