# Nếp Studio

Landing page tiếng Việt cho một studio chụp ảnh giả định. Mã nguồn dùng HTML và CSS. Ảnh WebP và font được lưu cùng trang nên có thể mở offline.

## Xem local

Mở [index.html](./index.html) trong trình duyệt. Chọn “Trao đổi về buổi chụp” để tới mục liên hệ. Thư mục `assets` chứa ảnh, font và giấy phép font.

## Đưa lên link công khai

1. Tạo một site tĩnh trên tài khoản hosting của bạn. Đặt thư mục `demo` làm thư mục xuất bản, với `index.html` ở gốc. Giữ nguyên đường dẫn tương đối tới `style.css` và `assets`. Trang chạy trực tiếp, không có lệnh build hay biến môi trường.
2. Xem bản preview của host. Kiểm tra lại hai ảnh, font tiếng Việt, điều hướng và CTA trên desktop/mobile. Giữ dòng “Nếp là studio giả định” để người xem hiểu mục đích của trang.
3. Dùng URL HTTPS của trang làm link demo trong hồ sơ. Mở URL trong cửa sổ riêng tư để xác nhận khách cũng truy cập được.

Chỉ đưa thư mục `demo` lên host. Ghi chú hồ sơ và evidence local để bàn giao riêng. Nếu dùng bản này cho studio thật, thay nội dung, ảnh và đích liên hệ bằng thông tin đã được studio duyệt.

## Nguồn hình ảnh và font

- [Chân dung](./assets/chan-dung.webp) và [tĩnh vật](./assets/san-pham.webp) là ảnh minh họa tạo bằng công cụ imagegen tích hợp, xuất từ hai nửa của cùng một ảnh. Người và sản phẩm trong ảnh là hư cấu.
- Font Lora được đóng gói kèm [giấy phép OFL](./assets/OFL-Lora.txt). [Nguồn font](https://fonts.google.com/specimen/Lora)

Prompt tạo ảnh:

> One wide 3:2 diptych photograph, perfectly vertical split down the middle with NO borders, each half composed as an independent portrait image to crop for a fictional Vietnamese photography studio website. Left half: editorial waist-up portrait of a fictional Vietnamese woman with dark hair and a dark olive jacket, eyes softly closed and head turned toward warm afternoon window light, cream plaster wall behind her, interesting broad shadows. Right half: a dark amber unbranded glass perfume bottle and a smooth beige stone on a limestone plinth against ochre plaster, angled sunlight. Analog editorial photography, lightly textured, warm cream and golden olive color grade, rich shadows. Subjects centered within respective halves. No text, typography, logo, collage borders or watermark.

## Bàn giao chặng 2

Năm phần, CTA nội trang, nguồn ảnh và hướng dẫn chạy đã nằm trong thư mục này. Bản mở trực tiếp đã qua kiểm tra ở ba viewport. [Kết quả và ảnh](../evidence/ket-qua.json)
