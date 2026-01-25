# Firmware QCC3031 unencrypted

### 1. Auto Bass Boost
- **Điều khiển**: Nhấn giữ PIO7 để bật/tắt
- **Mặc định**: Được bật sẵn khi khởi động
- **LED thông báo**: khi bassboost bật PIO6 ở mức cao, khi tắt PIO6 ở mức thấp

### 2. Crossover 2-way
- **Tần số cắt mặc định**: 3kHz, sử dụng QACT để tùy chỉnh lại tần số cắt mong muốn
- **Chế độ Mono**: Nối PIO5 lên mức cao (HIGH) để kích hoạt
- **Để tắt crossover**: Sử dụng ADK Config Tool để cấu hình output mapping về 2 kênh

### 3. TWS (True Wireless Stereo)
- **Ghép nối**: Nhấn một lần PIO7 để vào chế độ ghép nối TWS

### 4. Cấu hình Button
- **Mặc định**: Chỉ có PIO7 được kích hoạt sẵn
- **Tùy biến**: Sử dụng ADK Config Tool để thêm các button khác theo ý muốn
