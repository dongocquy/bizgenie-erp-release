# Bizgenie ERP System

Hệ thống quản lý doanh nghiệp tổng hợp được phát triển bằng DevExpress XAF (XPO) framework.

## 📋 Mô tả

Bizgenie ERP là một ứng dụng quản lý doanh nghiệp được xây dựng trên nền tảng DevExpress XAF với các tính năng:
- Quản lý nhân viên
- Quản lý thông tin căn hộ
- Theo dõi lịch sử chi trả HHMG
- Quản lý lịch sử tạm ứng HHMG

## 🚀 Phiên bản Release

**Version:** v1.0.0  
**Ngày phát hành:** 16/09/2025  
**Platform:** Windows (.NET 6.0)

## 📦 Cài đặt

1. Tải xuống file `BizgenieERP.Win.exe` từ repository này
2. Đảm bảo máy tính đã cài đặt .NET 6.0 Runtime
3. Chạy file thực thi để khởi động ứng dụng

## 📖 Hướng dẫn sử dụng

### Bước 1: Đăng nhập tài khoản

1. **Khởi động ứng dụng**
   - Chạy file `BizgenieERP.Win.exe`
   - Ứng dụng sẽ hiển thị màn hình đăng nhập

2. **Thông tin đăng nhập**
   - Nhập **Username** và **Password**
   - Nhấn nút **Login** để đăng nhập
   - Nếu chưa có tài khoản, liên hệ quản trị viên để được tạo

3. **Giao diện chính**
   - Sau khi đăng nhập thành công, bạn sẽ thấy Dashboard chính
   - Menu điều hướng nằm ở phía trái màn hình

### Bước 2: Tạo Nhân viên

1. **Truy cập module Nhân viên**
   - Từ menu chính, chọn **"Danh sách Nhân viên"**
   - Hoặc tìm kiếm "Nhân viên" trong thanh tìm kiếm

2. **Thêm nhân viên mới**
   - Nhấn nút **"New"** hoặc **"Thêm mới"**
   - Điền thông tin nhân viên:
     - **Họ và tên**: Tên đầy đủ của nhân viên
     - **Mã nhân viên**: Mã số định danh duy nhất
     - **Phòng ban**: Bộ phận làm việc
     - **Chức vụ**: Vị trí công việc
     - **Ngày vào làm**: Ngày bắt đầu làm việc
     - **Lương cơ bản**: Mức lương cơ bản
     - **Thông tin liên hệ**: Số điện thoại, email

3. **Lưu thông tin**
   - Kiểm tra lại thông tin đã nhập
   - Nhấn nút **"Save"** để lưu
   - Nhấn **"Save & Close"** để lưu và đóng form

### Bước 3: Tạo Thông tin Căn hộ

1. **Truy cập module Căn hộ**
   - Từ menu chính, chọn **"Danh sách Căn hộ"**
   - Hoặc tìm kiếm "Căn hộ" trong thanh tìm kiếm

2. **Thêm căn hộ mới**
   - Nhấn nút **"New"** hoặc **"Thêm mới"**
   - Điền thông tin căn hộ:
     - **Mã căn hộ**: Mã số định danh căn hộ
     - **Tên căn hộ**: Tên hoặc số căn hộ
     - **Tầng**: Tầng của căn hộ
     - **Diện tích**: Diện tích căn hộ (m²)
     - **Số phòng**: Số phòng trong căn hộ
     - **Giá thuê**: Giá thuê hàng tháng
     - **Trạng thái**: Trống/Đã thuê/Bảo trì
     - **Mô tả**: Thông tin bổ sung về căn hộ

3. **Lưu thông tin**
   - Kiểm tra lại thông tin đã nhập
   - Nhấn nút **"Save"** để lưu
   - Nhấn **"Save & Close"** để lưu và đóng form

### Bước 4: Tạo lịch sử Chi trả HHMG

1. **Truy cập module Chi trả**
   - Từ menu chính, chọn **"Lịch sử Chi trả HHMG"**
   - Hoặc tìm kiếm "Chi trả" trong thanh tìm kiếm

2. **Thêm bản ghi chi trả mới**
   - Nhấn nút **"New"** hoặc **"Thêm mới"**
   - Điền thông tin chi trả:
     - **Mã giao dịch**: Mã số giao dịch tự động
     - **Nhân viên**: Chọn nhân viên từ danh sách
     - **Căn hộ**: Chọn căn hộ từ danh sách
     - **Ngày chi trả**: Ngày thực hiện chi trả
     - **Số tiền**: Số tiền chi trả
     - **Loại chi trả**: Tiền thuê/Tiền điện/Tiền nước/Khác
     - **Phương thức**: Tiền mặt/Chuyển khoản
     - **Ghi chú**: Mô tả chi tiết về khoản chi trả

3. **Lưu thông tin**
   - Kiểm tra lại thông tin đã nhập
   - Nhấn nút **"Save"** để lưu
   - Nhấn **"Save & Close"** để lưu và đóng form

### Bước 5: Tạo lịch sử Tạm ứng HHMG

1. **Truy cập module Tạm ứng**
   - Từ menu chính, chọn **"Lịch sử Tạm ứng HHMG"**
   - Hoặc tìm kiếm "Tạm ứng" trong thanh tìm kiếm

2. **Thêm bản ghi tạm ứng mới**
   - Nhấn nút **"New"** hoặc **"Thêm mới"**
   - Điền thông tin tạm ứng:
     - **Mã giao dịch**: Mã số giao dịch tự động
     - **Nhân viên**: Chọn nhân viên từ danh sách
     - **Căn hộ**: Chọn căn hộ từ danh sách
     - **Ngày tạm ứng**: Ngày thực hiện tạm ứng
     - **Số tiền**: Số tiền tạm ứng
     - **Lý do tạm ứng**: Mục đích sử dụng tiền
     - **Ngày hoàn trả dự kiến**: Ngày dự kiến hoàn trả
     - **Trạng thái**: Chưa hoàn trả/Đã hoàn trả một phần/Đã hoàn trả
     - **Ghi chú**: Mô tả chi tiết về khoản tạm ứng

3. **Lưu thông tin**
   - Kiểm tra lại thông tin đã nhập
   - Nhấn nút **"Save"** để lưu
   - Nhấn **"Save & Close"** để lưu và đóng form

## 🔧 Tính năng bổ sung

### Tìm kiếm và Lọc
- Sử dụng thanh tìm kiếm để tìm nhanh các bản ghi
- Áp dụng bộ lọc để hiển thị dữ liệu theo điều kiện
- Sắp xếp dữ liệu theo các cột khác nhau

### Báo cáo
- Xuất dữ liệu ra Excel/PDF
- Tạo báo cáo tổng hợp theo thời gian
- In danh sách các bản ghi

### Quản lý dữ liệu
- Chỉnh sửa thông tin đã tạo
- Xóa các bản ghi không cần thiết
- Sao lưu và khôi phục dữ liệu

## ⚠️ Lưu ý quan trọng

1. **Backup dữ liệu**: Thường xuyên sao lưu dữ liệu quan trọng
2. **Quyền truy cập**: Chỉ người có quyền mới được chỉnh sửa dữ liệu
3. **Kiểm tra thông tin**: Luôn kiểm tra kỹ thông tin trước khi lưu
4. **Cập nhật**: Thường xuyên cập nhật ứng dụng để có tính năng mới

## 🆘 Hỗ trợ

Nếu gặp vấn đề trong quá trình sử dụng:
- Kiểm tra kết nối mạng
- Khởi động lại ứng dụng
- Liên hệ bộ phận IT để được hỗ trợ

## 📞 Liên hệ

- **Email hỗ trợ**: support@bizgenie.com
- **Hotline**: 1900-xxxx
- **Website**: https://bizgenie.com

---

**Bizgenie ERP System v1.0.0**  
*Phát triển bởi Bizgenie Team*
