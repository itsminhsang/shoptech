# 🛒 ShopTech - Website Thương Mại Điện Tử

Website thương mại điện tử chuyên bán các sản phẩm công nghệ như điện thoại, laptop, tablet và phụ kiện.

## ✨ Tính Năng

### Dành cho Khách Hàng
- **Trang chủ**: Hiển thị sản phẩm bán chạy và sản phẩm mới nhất
- **Danh sách sản phẩm**: Xem tất cả sản phẩm với bộ lọc theo danh mục
- **Tìm kiếm**: Tìm kiếm sản phẩm theo tên hoặc danh mục
- **Chi tiết sản phẩm**: Xem thông tin chi tiết của từng sản phẩm
- **Giỏ hàng**: 
  - Thêm/xóa sản phẩm
  - Điều chỉnh số lượng
  - Xem tổng giá trị đơn hàng
- **Đặt hàng**: Hoàn tất mua hàng và nhận mã đơn hàng

### Dành cho Quản Trị Viên
- **Dashboard quản lý**: Giao diện quản trị toàn diện
- **Quản lý sản phẩm**:
  - Thêm sản phẩm mới
  - Xóa sản phẩm
  - Xem danh sách và thống kê sản phẩm
- **Quản lý danh mục**: Xem số lượng sản phẩm theo từng danh mục
- **Quản lý đơn hàng**: 
  - Xem danh sách đơn hàng
  - Cập nhật trạng thái đơn hàng
- **Quản lý khách hàng**: Xem thông tin và lịch sử mua hàng
- **Thống kê**: 
  - Tổng doanh thu
  - Số lượng đơn hàng
  - Sản phẩm đã bán
  - Số lượng khách hàng

## 🚀 Cài Đặt và Chạy

### Yêu Cầu
- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge)
- Không cần cài đặt thêm bất kỳ phần mềm nào

### Cách Chạy
1. Tải file `shoptech.html` về máy
2. Mở file bằng trình duyệt web
3. Website sẽ hoạt động ngay lập tức

## 👤 Tài Khoản Demo

### Tài Khoản Quản Trị Viên
- **Email**: `admin@shop.com`
- **Mật khẩu**: `admin123`

## 📱 Danh Mục Sản Phẩm

- **Điện thoại**: iPhone, Samsung, Xiaomi
- **Laptop**: MacBook, Dell XPS
- **Tablet**: iPad Pro
- **Phụ kiện**: AirPods, Apple Watch

## 🎨 Công Nghệ Sử Dụng

- **HTML5**: Cấu trúc trang web
- **CSS3**: Thiết kế giao diện
  - Flexbox & Grid Layout
  - Gradient backgrounds
  - Animations & Transitions
  - Responsive design
- **JavaScript (Vanilla)**: Xử lý logic
  - DOM manipulation
  - Event handling
  - Local data management
  - Dynamic rendering

## 📂 Cấu Trúc Dự Án

```
shoptech.html
├── Header
│   ├── Logo
│   ├── Thanh tìm kiếm
│   └── Nút đăng nhập & giỏ hàng
├── Navigation Menu
├── Pages
│   ├── Trang chủ (Home)
│   ├── Sản phẩm (Products)
│   ├── Giỏ hàng (Cart)
│   └── Trang quản trị (Admin Panel)
└── Modals
    ├── Đăng nhập
    └── Chi tiết sản phẩm
```

## 💡 Hướng Dẫn Sử Dụng

### Cho Khách Hàng
1. Duyệt sản phẩm trên trang chủ hoặc trang sản phẩm
2. Click vào sản phẩm để xem chi tiết
3. Nhấn "Thêm vào giỏ" để thêm sản phẩm
4. Vào giỏ hàng để xem và điều chỉnh đơn hàng
5. Nhấn "Đặt hàng" để hoàn tất mua hàng

### Cho Quản Trị Viên
1. Nhấn "Đăng nhập" và sử dụng tài khoản admin
2. Hệ thống sẽ chuyển đến trang quản trị
3. Sử dụng các tab để quản lý:
   - **Sản phẩm**: Thêm, xóa sản phẩm
   - **Danh mục**: Xem thống kê danh mục
   - **Đơn hàng**: Quản lý và cập nhật trạng thái
   - **Khách hàng**: Xem thông tin khách hàng
   - **Thống kê**: Xem báo cáo tổng quan

## 🔧 Tính Năng Kỹ Thuật

- **Single Page Application (SPA)**: Không reload trang khi chuyển đổi
- **Responsive Design**: Tương thích với nhiều kích thước màn hình
- **Dynamic Content**: Nội dung được render động bằng JavaScript
- **Modal System**: Hệ thống popup linh hoạt
- **Local State Management**: Quản lý dữ liệu trong bộ nhớ trình duyệt

## 🎯 Các Chức Năng Chính

### Hệ Thống Giỏ Hàng
- Thêm sản phẩm với số lượng tùy chọn
- Tăng/giảm số lượng sản phẩm
- Xóa sản phẩm khỏi giỏ
- Tính toán tổng giá trị tự động
- Badge hiển thị số lượng sản phẩm

### Hệ Thống Lọc và Tìm Kiếm
- Lọc sản phẩm theo danh mục
- Tìm kiếm theo tên và danh mục
- Hiển thị kết quả động

### Hệ Thống Đơn Hàng
- Tạo đơn hàng tự động
- Sinh mã đơn hàng duy nhất
- Cập nhật số lượng đã bán
- Quản lý trạng thái đơn hàng (4 trạng thái)

## 📊 Dữ Liệu Mẫu

Website đi kèm với:
- 8 sản phẩm mẫu
- 3 khách hàng mẫu
- 4 danh mục sản phẩm
- Dữ liệu thống kê động

## 🎨 Thiết Kế UI/UX

- **Color Scheme**: Gradient tím (#667eea → #764ba2)
- **Typography**: Segoe UI font family
- **Layout**: Modern card-based design
- **Icons**: Emoji icons cho sản phẩm
- **Animations**: Smooth transitions và hover effects

## 📝 Lưu Ý

- Dữ liệu được lưu trong bộ nhớ tạm (không persist khi reload)
- Đây là bản demo, không kết nối database thực
- Phù hợp cho mục đích học tập và demo

## 👨‍💻 Tác Giả

**Sony** (nickname)

## 📄 Bản Quyền

© 2025 Lại Trần Minh Sang. All rights reserved.

Dự án này được tạo cho mục đích học tập và demo.

---

**Phát triển bởi Sony (itsminhsang) - ShopTech E-commerce Platform**
