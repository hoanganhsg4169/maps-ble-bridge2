========================================================================
       HƯỚNG DẪN IMPORT VÀ BIÊN DỊCH ỨNG DỤNG ANDROID MAPS BLE BRIDGE
========================================================================

Ứng dụng này đã được cấu hình sẵn sàng 100% để import trực tiếp vào Android Studio.

CÁC BƯỚC THỰC HIỆN:
-----------------
Bước 1: Giải nén tệp tin .zip này ra một thư mục.
Bước 2: Mở ứng dụng Android Studio (Khuyến nghị phiên bản Flamingo trở lên).
Bước 3: Chọn File -> Open, tìm và dẫn tới thư mục vừa giải nén.
Bước 4: Chờ Android Studio đồng bộ Gradle tự động (Quá trình này mất khoảng 2-5 phút).
Bước 5: Cắm điện thoại Android của bạn vào máy tính (Bật chế độ Nhà phát triển & USB Debugging).
Bước 6: Nhấn nút Run (Biểu tượng tam giác xanh lá trên thanh công cụ) để cài ứng dụng trực tiếp.
Bước 7: Để xuất file .apk cài đặt thủ công: Chọn Build -> Build Bundle(s) / APK(s) -> Build APK(s).

LƯU Ý QUAN TRỌNG:
----------------
- App sử dụng Bluetooth Low Energy (BLE) và Notification Access để lọc thông báo từ Google Maps.
- Hãy cấp quyền "Truy cập thông báo" cho ứng dụng ngay khi mở app trong trang Cài đặt.
- Cấu hình BLE hiện tại của bạn:
  + Service UUID: 0000ffe0-0000-1000-8000-00805f9b34fb
  + Characteristic UUID: 0000ffe1-0000-1000-8000-00805f9b34fb
========================================================================
