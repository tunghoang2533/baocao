> **CẬP NHẬT 13/10/2026:** Đã sửa trực tiếp vào file `.docx` tất cả các mục dưới đây, **trừ ảnh Chương 3** (giữ nguyên 15 vị trí placeholder tô đỏ để chờ chèn ảnh). Sau khi mở file bằng Word/WPS lần đầu, chọn **Ctrl+A → F9 → Update entire table** để cập nhật số trang cho Mục lục, Danh mục bảng và Danh mục hình. Chi tiết từng mục đã sửa xem trong bản tóm tắt kèm theo.

# KẾT QUẢ KIỂM TRA BÁO CÁO
**File:** `Bao_cao_Do_an_Website_Ban_Linh_Kien_da_sua_hoan_thien.docx`
**Ngày kiểm tra:** 13/10/2026 · **Phạm vi:** nội dung, cấu trúc chương/mục, đánh số hình–bảng, danh mục, tính nhất quán giữa các chương (trích xuất và đối chiếu toàn văn + 63 bảng + toàn bộ chú thích hình/bảng trong file)

> Kết luận nhanh: **Chưa nên nộp ngay.** Khung nội dung 4 chương khá đầy đủ, nhưng còn **5 lỗi nghiêm trọng** (mục 1) sẽ bị giảng viên phát hiện ngay khi mở file. Sửa xong 5 lỗi đó + cập nhật lại danh mục là có thể nộp được.

---

## 1. LỖI NGHIÊM TRỌNG — bắt buộc sửa trước khi nộp

### 1.1. Chương 3 không có bất kỳ hình giao diện nào — chỉ có dòng placeholder
Toàn bộ 15 mục giao diện (Hình 3.1 → 3.15) đều chỉ có một dòng chữ dạng:

> `[Hình ảnh / Sơ đồ minh họa: Giao diện trang chủ hệ thống bán linh kiện điện tử PC Store]`

rồi đến chú thích "Hình 3.x: ..." — **không có ảnh chụp màn hình thật nào được chèn**. Đây là chương "Thiết kế giao diện" nên lỗi này nặng nhất: danh mục hình vẫn ghi số trang cho các hình không tồn tại.
→ Chạy website, chụp màn hình thật của từng trang, thay vào đúng vị trí placeholder, xóa dòng chữ `[...]`.

Kèm theo: dòng thừa **`Code giao diện trang quản lý đánh giá:`** (sau Hình 3.14) bị bỏ dở — không có code/hình nào theo sau. Xóa dòng này hoặc bổ sung nội dung.

### 1.2. Không có MỤC LỤC
File chỉ có *Danh mục bảng biểu* và *Danh mục hình ảnh*, **thiếu hẳn trang Mục lục** của báo cáo. Hầu hết quy định của trường đều yêu cầu mục lục tự động.
→ Chèn mục lục (References → Table of Contents) sau trang bìa phụ/trước Mở đầu — nhưng phải sửa xong lỗi 1.3 trước, nếu không mục lục sẽ sai.

### 1.3. Tiêu đề Chương 4 và phần Kết luận không dùng Heading — cấu trúc bị gãy
- `KIỂM THỬ HỆ THỐNG` (tiêu đề chương 4) đang là **Normal**, không phải Heading 1 → mọi mục kiểm thử (4.x) đang bị "treo" dưới Chương 3 trong cây heading/mục lục.
- `KẾT LUẬN VÀ HƯỚNG PHÁT TRIỂN` đang là **List Paragraph**, không phải Heading 1.
- Các Heading 1 còn lại **không có số chương** ("TỔNG QUAN VỀ ĐỀ TÀI NGHIÊN CỨU" thay vì "CHƯƠNG 1: ..."), trong khi toàn văn lại tham chiếu "Chương 1/2/3/4", "mục 2.6" — người đọc không đối chiếu được.
- Mục con của Kết luận đánh số lệch: "Kết quả đạt được" không có số 1., nhưng các mục sau lại là "2. Hạn chế", "3. Kiến nghị", "4. Hướng phát triển".

→ Gán Heading 1 cho 2 tiêu đề trên; thống nhất mẫu tiêu đề chương (VD: `CHƯƠNG 1 – TỔNG QUAN...` hoặc bật numbering tự động); đánh lại số cho mục "1. Kết quả đạt được".

### 1.4. Danh mục hình ảnh đã lỗi thời, lệch từ Hình 3.4 trở đi
Danh mục hình dừng ở Hình 3.13, trong khi nội dung có tới Hình 3.15. Từ Hình 3.4 trở đi tên hình trong danh mục **không khớp** nội dung (do chèn thêm 2 giao diện mà chưa cập nhật danh mục):

| Danh mục ghi | Nội dung thực tế |
|---|---|
| Hình 3.4: Giao diện giỏ hàng | Hình 3.4: Giao diện trang đơn hàng của tôi |
| Hình 3.5: Giao diện đăng nhập | Hình 3.5: Giao diện giỏ hàng |
| Hình 3.6: Giao diện trang báo cáo thống kê | Hình 3.6: Giao diện đăng nhập |
| ...lệch tiếp đến hết chương 3 | Thiếu hẳn: Hình 3.7 (đăng ký), Hình 3.15 (khuyến mãi bị ghi là 3.13) |

### 1.5. Danh mục bảng thiếu 11 bảng + vị trí "Kết luận chương" bị chèn giữa chừng
- **Bảng 2.15 → 2.25** (cấu trúc 11 bảng CSDL) không có trong Danh mục bảng biểu, vì chúng đang được đặt style **Heading 3** thay vì **Caption** → vừa vắng mặt trong danh mục, vừa làm bẩn cây heading/mục lục (mục lục sẽ liệt kê 11 "mục" giả này).
- **"Kết luận chương" (cuối Chương 2) bị kẹp giữa Bảng 2.23 và Bảng 2.24**: thứ tự hiện tại là …Bảng 2.23 → *Kết luận chương* → Bảng 2.24 → đoạn kết luận → Bảng 2.25. Phải chuyển cả 2 bảng 2.24/2.25 lên trước mục Kết luận chương.

→ Sau khi sửa style/xong xuôi: **Ctrl+A → F9 → Update entire table** cho cả 2 danh mục (và mục lục mới) để cập nhật tên + số trang.

---

## 2. LỖI NỘI DUNG / NHẤT QUÁN — nên sửa

1. **Hình 2.19 chú thích sai style**: chú thích "Hình 2.19: Sơ đồ tuần tự quản lý đánh giá" là Normal, không phải Caption (các hình khác đều là Caption) → sẽ mất khi cập nhật danh mục tự động.
2. **25 đoạn Caption rỗng** đang chứa hình (hình bị đặt trong paragraph Caption trống). Nên để hình ở Normal, chú thích Caption nằm riêng phía dưới — nếu không, khi update field, danh mục sẽ sinh dòng trắng/lỗi.
3. **14 bảng mô tả lớp (biên/điều khiển/thực thể) ở phần sơ đồ tuần tự không có số, không chú thích, không được nhắc tới trong văn bản** → đánh số Bảng 2.x nối tiếp hoặc gộp/xóa; hiện chúng "trôi" giữa các hình.
4. **Sơ đồ Use Case thiếu hình cho 4 chức năng**: đăng ký, đăng nhập, tìm kiếm, thống kê doanh thu chỉ có bảng mô tả, không có sơ đồ (8 chức năng còn lại có cả hai). Bổ sung hình hoặc ghi rõ "đã thể hiện trong sơ đồ tổng quát".
5. **Mâu thuẫn ERD ↔ thiết kế CSDL (Chương 2 tự mâu thuẫn):**
   - ERD tách 2 thực thể *Quản trị viên* và *Khách hàng*, nhưng CSDL gộp vào 1 bảng `Users` (có `role`). Cần giải thích ánh xạ hoặc sửa ERD.
   - ERD mô tả *Giỏ hàng* chứa thẳng `Mã_SP, Số_lượng`, nhưng CSDL tách `Carts` + `Cart_items`; ERD ở phần quan hệ lại nhắc "Chi tiết giỏ hàng" — danh sách thực thể thiếu: Danh mục, Đánh giá, Kho, Cart_items (ERD liệt kê 8 thực thể, CSDL có 11 bảng).
   - `Products.quantity` và `Inventories.quantity_in_stock` cùng lưu tồn kho → nguy cơ lệch dữ liệu, chưa thấy đoạn giải thích cơ chế đồng bộ.
6. **Vai trò "nhân viên" xuất hiện 1 lần duy nhất** (mô tả trang đăng nhập, Chương 3) trong khi toàn hệ thống chỉ có 2 tác nhân Khách hàng/Quản trị viên → sửa thành 2 vai trò cho thống nhất.
7. **Chương 3 thiếu giao diện đặt hàng/thanh toán (checkout + VNPay)** — chức năng trung tâm, có kiểm thử ở Chương 4 (Bảng 4.6) nhưng không có mục giao diện tương ứng; mục "Giao diện trang sản phẩm" có 2 đoạn "Mô tả:" liên tiếp (trang danh sách và trang chi tiết bị gộp, chưa tách mục).
8. **Tài liệu tham khảo quá yếu**: chỉ 4 mục, đều cũ (2003, 2012, 2014, 2018); không có tài liệu chính thức của Laravel/PHP/MySQL/Bootstrap/VNPay dù đây là công nghệ cốt lõi của đề tài; **không có bất kỳ trích dẫn nào trong thân bài**; định dạng không thống nhất (mục [2] thiếu tác giả). Bổ sung nguồn chính thức + gắn trích dẫn tại các đoạn lý thuyết (UML, MVC, kiểm thử...).
9. **Trang bìa chưa thống nhất tên gọi**: bìa ghi "BÁO CÁO BÀI TẬP LỚN", tên file + Mở đầu/Kết luận gọi là "đồ án" → chọn 1 cách gọi theo đúng yêu cầu của trường/khoa.
10. **Số liệu kiểm thử hiệu năng/bảo mật chưa có bằng chứng**: Bảng 4.18 ghi "đo 100 lần, trung bình ≈1,2s" nhưng không có biểu log/số liệu thô, và chỉ đo trên localhost. Không sai, nhưng nếu giảng viên hỏi "số liệu lấy ở đâu" sẽ khó trả lời — nên đính kèm ít nhất 1 ảnh chụp Chrome DevTools/Postman hoặc ghi rõ cách đo.

## 3. LỖI NHỎ — chính tả, trình bày

- Trang bìa phụ có ký tự thừa **`\`** đứng một mình (giữa trang).
- Heading "Sơ đồ tuần **tự** đăng nhập" lỗi font/chữ tổ hợp (dấu nặng tách rời); nhiều heading thừa dấu cách ở đầu (" Tổng quan...", " Sơ đồ tuần tự"...).
- Thuật ngữ không thống nhất: `Usecase` (48 lần) / `Use Case` (10) / `usecase` (2, trong "Bảng 2.1: Mô tả usecase đăng ký"); chữ `Bảng/Hình` trộn 2 kiểu gõ Unicode (tổ hợp & dựng sẵn) — nên chuẩn hóa 1 kiểu, tìm–thay toàn bộ.
- Thiếu dấu cách sau dấu chấm: "...từng chức năng.**Trong** hệ thống PC Store..." (mục Tổng quan sơ đồ tuần tự).
- Bảng điểm/bảng thông tin đầu file: dòng "Vàng A Sử 2211060491" bị gộp 1 dòng (3 bạn trên tách 2 dòng); cột Điểm để trống là phần của hội đồng — giữ nguyên nếu đúng mẫu trường.
- Thuộc tính file (Word Properties) còn author **`thao pham phuong`** — người ngoài nhóm, dấu vết dùng lại file mẫu. Nên sửa File → Info → Properties (Author/Last Modified By) trước khi nộp; bìa ghi "Hà Nội – 2025" cũng nên đối chiếu năm nộp thực tế.

## 4. ĐIỂM ĐÃ LÀM TỐT (đã kiểm chứng, không cần sửa)

- ✅ **Số liệu kiểm thử khớp tuyệt đối**: tổng các bảng chi tiết 4.2–4.19 đúng **80 test case**; tổng hợp Bảng 4.20 (37 + 27 + 5 + 5 + 6 = 80; đạt ngay 76, sửa 4 lỗi = 100%) khớp với phần "Một số lỗi phát hiện và khắc phục" (đúng 4 lỗi: tồn kho, voucher hết hạn, XSS, tràn bảng trên mobile).
- ✅ Đánh số hình/bảng trong thân bài liên tục, không trùng/thiếu số (Hình 1.1; 2.1–2.27; Bảng 2.1–2.25; 4.1–4.20) — chỉ lỗi ở *danh mục* và *style*, không phải ở số thứ tự.
- ✅ Thiết kế CSDL chi tiết, có khóa ngoại rõ ràng (11 bảng); cấu trúc 4 chương + Mở đầu/Kết luận/TLTK đúng bố cục chuẩn; đã có số trang tự động ở footer.

## 5. THỨ TỰ SỬA GỢI Ý (làm theo thứ tự này để không phải update danh mục nhiều lần)

1. Chụp & chèn 15 ảnh giao diện Chương 3 (xóa placeholder + dòng "Code giao diện...").
2. Gán lại Heading 1 cho "KIỂM THỬ HỆ THỐNG" và "KẾT LUẬN VÀ HƯỚNG PHÁT TRIỂN"; chuyển Bảng 2.15–2.25 từ Heading 3 → Caption; dời Bảng 2.24/2.25 lên trước Kết luận Chương 2; sửa style chú thích Hình 2.19.
3. Thống nhất đánh số/tên chương, vai trò người dùng, thuật ngữ Use Case; rà mâu thuẫn ERD ↔ CSDL (mục 2.5 ở trên).
4. Bổ sung TLTK + trích dẫn; sửa lỗi nhỏ mục 3; sửa Properties của file.
5. Chèn Mục lục tự động → **Ctrl+A → F9** cập nhật toàn bộ (mục lục, danh mục bảng, danh mục hình, số trang) → mở từng danh mục đối chiếu lại tên hình/bảng lần cuối → xuất PDF kiểm tra vỡ trang trước khi nộp.
