# 🎁 dGiftcode v1.0.0 - Hệ thống Giftcode Chuyên nghiệp

<div align="center">
  <img src="https://img.shields.io/badge/Version-1.21-blue.svg">
  <img src="https://img.shields.io/badge/Release-Premium-gold.svg">
  <img src="https://img.shields.io/badge/Author-QuangDunz-orange.svg">
  <img src="https://img.shields.io/badge/License-Locked-red.svg">
</div>

---

**dGiftcode** là một plugin quản lý mã quà tặng (Giftcode) hàng đầu cho Minecraft Server, được thiết kế để mang lại trải nghiệm tối ưu cho cả người chơi và quản trị viên. Với hệ thống giao diện (GUI) hiện đại, logic nhận thưởng linh hoạt và tính năng tạo mã hàng loạt mạnh mẽ.

## ✨ Tính năng Nổi bật

*   **⚡ Trải nghiệm "Một Lệnh":** Người chơi chỉ cần dùng `/giftcode` để mở ngay giao diện nhập mã (Anvil GUI).
*   **📂 Quản trị GUI Toàn diện:** Admin quản lý toàn bộ mã qua giao diện đồ họa (Code List, Editor, Item Editor).
*   **🛠 Tạo mã Hàng loạt (Bulk):** Tạo hàng trăm mã chỉ trong 1 giây với cấu hình tùy chỉnh qua câu lệnh hoặc GUI.
*   **🛡 Bảo mật Đa lớp:** Giới hạn lượt dùng theo Người chơi, Địa chỉ IP, Thời gian Online và Quyền hạn (Permissions).
*   **🎆 Hiệu ứng Bắt mắt:** Tự động bắn pháo hoa, gửi Title, Sound và Broadcast khi người chơi nhận quà thành công.
*   **🔗 Tương thích Folia:** Chạy mượt mà trên cả máy chủ Spigot/Paper truyền thống và hệ thống Folia đa lõi.

## 📜 Hệ thống Lệnh (Commands)

### 👤 Cho Người chơi
| Lệnh | Mô tả |
| :--- | :--- |
| `/giftcode` | Mở giao diện Anvil để nhập mã quà tặng. |

### 👑 Cho Quản trị viên
| Lệnh | Mô tả |
| :--- | :--- |
| `/giftcode gui` | Mở giao diện danh sách mã để quản lý. |
| `/giftcode create <id> [-g]` | Tạo mã mới (Thêm `-g` để mở Tool tạo nâng cao). |
| `/giftcode delete <id>` | Xóa một mã khỏi hệ thống. |
| `/giftcode edit <id>` | Sửa thông số (Phần thưởng, Giới hạn...). |
| `/giftcode reward <id>` | Sửa vật phẩm quà tặng trong giao diện. |
| `/giftcode info <id>` | Xem chi tiết thông số và lượt dùng của mã. |
| `/giftcode bulk <số lượng>` | Tạo nhanh hàng loạt mã quà tặng. |
| `/giftcode status <id>` | Bật hoặc Tắt hoạt động của mã ngay lập tức. |
| `/giftcode reload` | Tải lại toàn bộ cấu hình plugin. |

## 🔑 Quyền hạn (Permissions)

*   `dgiftcode.admin`: Quyền sử dụng tất cả các lệnh quản trị và truy cập GUI Admin.

## 🚀 Cài đặt

1.  Tải plugin **dGiftcode.jar** và thư viện yêu cầu **dLib.jar**.
2.  Bỏ cả hai vào thư mục `/plugins/` của máy chủ.
3.  Khởi động server để plugin tự tạo cấu hình.
4.  Cài đặt các dịch vụ kinh tế (Vault) nếu muốn trao thưởng tiền tệ.

---

<p align="center">
  Phát triển bởi <b>QuangDunz</b>. Mọi quyền được bảo lưu.<br>
  <i>Plugin này yêu cầu dLib để xác thực bản quyền.</i>
</p>
