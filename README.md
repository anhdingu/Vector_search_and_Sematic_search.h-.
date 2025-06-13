# Website Giới Thiệu Công Ty Công Nghệ GIS

Đây là dự án xây dựng một website giới thiệu công ty hoạt động trong lĩnh vực công nghệ GIS (Geographic Information System), được lấy cảm hứng từ giao diện và bố cục của trang ekgis.com.vn.

## Mục tiêu dự án

- Tạo một website hiện đại, responsive, dễ sử dụng.
- Trình bày rõ ràng các dịch vụ, sản phẩm, tin tức và thông tin liên hệ.
- Dễ dàng mở rộng thành hệ thống CMS hoặc tích hợp backend sau này.

## Công nghệ sử dụng

- HTML5
- CSS3 (có thể mở rộng bằng Tailwind CSS hoặc Bootstrap)
- JavaScript thuần
- FontAwesome cho biểu tượng (tùy chọn)
- Thư viện hỗ trợ:
  - SwiperJS (nếu có slider)
  - AOS (Animation on Scroll – nếu cần hiệu ứng cuộn)
  - 
## cấu trúc dự án
gis-company-website/
├── index.html              # Trang chủ
├── about.html              # Giới thiệu
├── services.html           # Dịch vụ
├── products.html           # Sản phẩm
├── news.html               # Tin tức
├── contact.html            # Liên hệ
├── style/
│   └── main.css            # CSS chính
├── js/
│   └── main.js             # JavaScript chính
├── assets/
│   ├── images/             # Thư mục chứa ảnh minh họa, logo, banner...
│   ├── fonts/              # (Tùy chọn) Font chữ nếu có font riêng
│   └── icons/              # (Tùy chọn) SVG hoặc icon tuỳ chỉnh
├── libs/                   # (Tùy chọn) Các thư viện bên ngoài như SwiperJS, AOS
├── README.md               # Mô tả dự án
└── .gitignore              # Danh sách file/folder không đẩy lên GitHub



## Tính năng chính

- Giao diện thân thiện với người dùng, tối ưu cho desktop và thiết bị di động.
- Điều hướng đơn giản, rõ ràng.
- Mỗi dịch vụ và sản phẩm được trình bày dưới dạng khối rõ ràng, dễ tiếp cận.
- Dễ dàng mở rộng thêm phần tìm kiếm, chatbot, hoặc tích hợp API.

## Hướng dẫn sử dụng

1. Clone repository:
   ```bash
   git clone https://github.com/anhdingu/web-check.git
2. Mở file index.html bằng trình duyệt hoặc sử dụng extension Live Server nếu dùng VS Code.
3. Tùy chỉnh nội dung và hình ảnh theo nhu cầu của công ty.

## Ghi chú

Đây là bản tĩnh (static site). Nếu cần quản trị nội dung (CMS) hoặc tích hợp backend, có thể chuyển sang sử dụng một framework như React, Next.js hoặc tích hợp với hệ thống WordPress, Strapi.

Dự án hiện chưa có backend hoặc cơ sở dữ liệu.

