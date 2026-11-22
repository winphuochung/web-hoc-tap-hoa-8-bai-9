# Web/app học tập — Hóa học 8, Bài 9

**Bài 9: Base. Thang pH**
Môn Khoa học tự nhiên 8 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Dung dịch NaOH làm giấy quỳ tím chuyển sang màu xanh (Thí nghiệm 1, SGK trang 40).
2. Phản ứng trung hoà giữa dung dịch NaOH và dung dịch HCl với phenolphthalein — 3 ống nghiệm (Thí nghiệm 2, Hình 9.1, SGK trang 40).
3. Đo pH của 6 dung dịch bằng giấy pH (nước chanh, nước ngọt có gas, giấm ăn, nước lọc, dung dịch baking soda, nước rửa bát; SGK trang 42).

Châm ngôn intro: "Thang pH nhỏ bé đo được cả thế giới acid – base quanh em."
Châm ngôn outro: "Nắm vững thang pH, em đọc được tính chất của mọi dung dịch."

Khóa đáp án trắc nghiệm: 1B 2C 3A 4D 5C 6A 7B 8D 9C 10A.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm hiện lưu trên máy học sinh (localStorage). Tính năng gửi điểm về Google Sheets đang CHỜ link Apps Script /exec (Google hiện chặn tạo dự án mới); file `Code.gs` đã có sẵn để deploy sau.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa8_Bai09.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — mã Apps Script ghi điểm về Google Sheets (deploy sau khi Google mở lại việc tạo dự án).
- `assets-flow/` — 3 ảnh nền gốc (Gemini, 1376×768) + logo giáo viên.
