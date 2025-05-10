# 🎥 PVD Video Steganography

Dự án giấu tin vào video bằng kỹ thuật **PVD (Pixel Value Differencing)** kết hợp **Optimal Pixel Adjustment (OPA)**. Dự án bao gồm 5 nhiệm vụ chính, từ chuyển tin thành bit, giấu tin, trích xuất tin, kiểm tra dung lượng video đến so sánh đặc trưng thống kê.

---

## ✅ Nhiệm vụ 1: Chuyển đoạn tin thành bit

- **File**: `messtobit.py`
- **Chức năng**: Chuyển thông điệp văn bản thành chuỗi bit để giấu vào video.
- **Cách dùng**:
  ```bash
  nano messtobit.py      # Chỉnh sửa thông điệp
  python3 messtobit.py   # Chạy chương trình

## ✅ Nhiệm vụ 2: Giấu đoạn tin “em yêu anh nhieu lam”

- **File**: PVD.py
- **Chức năng**: Nhúng thông điệp vào video bằng kỹ thuật PVD
- **Cách dùng**:
  ```bash
nano PVD.py            # Chỉnh sửa thông điệp nếu cần
python3 PVD.py         # Chạy chương trình giấu tin

  ## ✅Nhiệm vụ 3: Giải tin

- **File**: PVD_extracted.py
- **Chức năng**: Giải mã và trích xuất thông điệp từ video đã nhúng tin.
- **Cách dùng**:
  ```bash
nano PVD_extracted.py  # Xem hoặc chỉnh sửa code nếu cần
python3 PVD_extracted.py

  ## ✅Nhiệm vụ 4: Kiểm tra dung lượng video xuất ra


- **File**: checksize.py
- **Chức năng**: Hiển thị dung lượng video sau khi đã giấu tin để so sánh với video gốc.
- **Cách dùng**:
  ```bash
nano checksize.py
python3 checksize.py

  ## ✅Nhiệm vụ 5: So sánh video gốc và video đã giấu tin


- **File**: compare_stats.py
- **Chức năng**:  So sánh các đặc trưng thống kê giữa video gốc và video chứa tin (như histogram, PSNR...)
- **Cách dùng**:
  ```bash
nano compare_stats.py
python3 compare_stats.py
