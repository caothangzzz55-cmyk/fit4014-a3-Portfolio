# Portfolio cá nhân – Kiều Cao Thăng

**Bài tập lớn A3 – FIT4014: Thiết kế Web và Triển khai HTPM**  
**Chủ đề:** Website portfolio giới thiệu bản thân  
**Sinh viên:** Kiều Cao Thăng – **MSV:** 2071020168

## 1. Giới thiệu dự án

Đây là website portfolio cá nhân được xây dựng bằng HTML5 và CSS3. Website giới thiệu thông tin cá nhân, kỹ năng đang học, quá trình học tập, các dự án và thông tin liên hệ.

Đối tượng người xem gồm giảng viên, bạn bè và người muốn tìm hiểu về quá trình học tập, sản phẩm của sinh viên.

## 2. Công nghệ sử dụng

- HTML5: xây dựng nội dung và cấu trúc trang.
- CSS3: thiết kế giao diện, Flexbox, Grid, hiệu ứng và responsive.
- Google Fonts – Be Vietnam Pro: hiển thị nội dung tiếng Việt.
- Git/GitHub và GitHub Pages: quản lý mã nguồn, triển khai website (sinh viên cần tự cấu hình trước khi nộp).

Dự án hiện sử dụng HTML/CSS thuần, không dùng framework và không có JavaScript.

## 3. Tính năng chính

- Menu điều hướng tới các phần Giới thiệu, Kỹ năng, Hành trình, Dự án và Liên hệ.
- Khu vực giới thiệu bản thân ở đầu trang.
- Các phần nội dung trình bày kỹ năng, quá trình học tập và dự án.
- Bố cục tự điều chỉnh theo màn hình máy tính và điện thoại.
- Biểu mẫu liên hệ sử dụng kiểm tra dữ liệu cơ bản của HTML5. Biểu mẫu dùng `mailto`, không lưu dữ liệu trên máy chủ.

## 4. Cấu trúc thư mục

```text
A3_Portfolio_KieuCaoThang/
├── index.html
├── css/
│   └── styles.css
├── assets/
│   └── images/
│   
├── docs/
│   ├── BAO_CAO.docx
│   ├── AI_LOG.md
│   ├── evidence-index.md
│   └── evidence/
│       ├── giao-dien-man-hinh-hep.png
│       ├── giao-dien-man-hinh-rong.png
│       └── kiem-thu-tu-dong.txt
├── CHANGELOG.md
└── README.md
```

## 5. Cách chạy website

1. Tải hoặc giải nén toàn bộ thư mục dự án.
2. Mở thư mục bằng Visual Studio Code.
3. Mở tệp `index.html` bằng trình duyệt; hoặc sử dụng tiện ích Live Server.
4. Không di chuyển riêng `index.html` hoặc thư mục `css`, vì trang cần đường dẫn `css/styles.css`.

## 6. Triển khai GitHub Pages

1. Tạo repository trên GitHub.
2. Đưa toàn bộ nội dung thư mục dự án lên repository.
3. Vào **Settings → Pages**.
4. Chọn nhánh `main` và thư mục `/ (root)`, sau đó lưu.
5. Chờ GitHub Pages triển khai và mở URL được cung cấp để kiểm tra.

**Repository:** (https://github.com/caothangzzz55-cmyk/fit4014-a3-Portfolio.git)  
**Website:** (https://caothangzzz55-cmyk.github.io/fit4014-a3-Portfolio/)

## 7. Tài liệu và minh chứng

- Báo cáo: `docs/BAO_CAO.md` và `docs/BAO_CAO.docx`.
- Nhật ký sử dụng AI: `docs/AI_LOG.md`.
- Chuẩn bị vấn đáp: `docs/VAN_DAP.md`.
- Kịch bản trình bày: `docs/KICH_BAN_DEMO.md`.
- Checklist trước khi nộp: `docs/CHECKLIST_NOP_BAI.md`.
- Danh mục minh chứng: `docs/evidence-index.md`.

## 8. Hạn chế và việc cần hoàn thiện

- Cần thay các nội dung mẫu/placeholder trong website bằng thông tin đã được sinh viên xác nhận.
- Form liên hệ chỉ mở ứng dụng email thông qua `mailto`; website chưa có backend hoặc cơ sở dữ liệu.
- Cần tự kiểm tra lại website trên trình duyệt, điện thoại và URL GitHub Pages thực tế.
- Cần cập nhật URL, repository, lịch sử commit và phiên bản sau khi triển khai.

## 9. Ghi nhận tài liệu tham khảo cấu trúc

Cách tổ chức thư mục và tài liệu tham khảo theo repository mẫu FIT4014 Audi Việt Nam:  
https://github.com/vanhkazen/fit4014-a3-audi-vietnam

Nội dung và chủ đề của dự án này vẫn là portfolio cá nhân; chỉ áp dụng cách phân chia thư mục và tổ chức tài liệu, không sao chép nội dung website Audi.
