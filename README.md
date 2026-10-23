# 📄 DOCX Deep Optimizer - Nén & Giảm Dung Lượng File Word Chuyên Sâu

> Công cụ web HTML5 tối ưu hóa và giảm dung lượng file Word (`.docx`) chạy **100% Client-Side** ngay trên trình duyệt. Không cần cài đặt, không tải tài liệu lên máy chủ, bảo mật tuyệt đối.

🌐 **Dùng trực tiếp Online tại:** [https://chauphan708.github.io/giamdungluongword/](https://chauphan708.github.io/giamdungluongword/)

---

## ✨ Điểm nổi bật

- **🔒 Bảo mật & Riêng tư 100%:** Toàn bộ quá trình giải nén, resize ảnh, nén dữ liệu và đóng gói diễn ra cục bộ trong bộ nhớ RAM trình duyệt. Không có bất kỳ byte dữ liệu nào gửi lên Internet.
- **⚡ Nén hàng loạt (Batch Processing):** Kéo thả cùng lúc hàng chục file Word, theo dõi tiến trình nén từng file thời gian thực và tải về toàn bộ bằng 1 nút bấm (file ZIP).
- **🎯 4 Chế độ nén tối ưu:**
  - **Tiêu chuẩn (Giảm ~60%):** Max 1600px, chất lượng 82%. Phù hợp in ấn A4 sắc nét.
  - **Nén sâu (Giảm 80% – 90% - Khuyên dùng):** Max 1200px, chất lượng 68%. Tự động phát hiện và chuyển đổi ảnh PNG chụp màn hình sang JPG, xóa file Thumbnail ẩn của Word.
  - **Siêu nén cực hạn (Giảm 90% – 96%):** Max 800px, chất lượng 50%. Ép toàn bộ ảnh sang JPG, nén ZIP Deflate Level 9 tối đa.
  - **Trắng đen siêu nhẹ (Giảm 92% – 98%):** Chuyển ảnh sang thang độ xám (Grayscale). Lý tưởng cho giáo án, bài giảng, đề thi trắc nghiệm in photo.
- **🛡️ Bảo toàn văn bản 100%:** Chỉ tối ưu hóa các hình ảnh trong thư mục `word/media/`, giữ nguyên hoàn toàn font chữ, định dạng, bảng biểu, công thức Toán, hình vẽ khối (Shape) và bookmark.

---

## 🚀 Hướng dẫn sử dụng

### Cách 1: Sử dụng Online
Truy cập liên kết [https://chauphan708.github.io/giamdungluongword/](https://chauphan708.github.io/giamdungluongword/) để dùng ngay trên bất kỳ thiết bị nào (Máy tính, Laptop, Điện thoại).

### Cách 2: Sử dụng Offline trên máy tính (Không cần mạng)
1. Tải file [DocxImageCompressor.zip](DocxImageCompressor.zip) về máy tính.
2. Giải nén và nhấp đúp vào `DocxImageCompressor.html` (hoặc `index.html`) để mở bằng trình duyệt (Chrome, Edge, Cốc Cốc, Firefox...).
3. Kéo thả các file `.docx` vào khung và bấm **"Bắt đầu nén"**.

---

## 🛠️ Công nghệ sử dụng
- **HTML5 / CSS3 / Vanilla JavaScript** (Zero-dependency ngoài, thư viện JSZip được nhúng sẵn bên trong file).
- **HTML5 Canvas 2D API** hỗ trợ tăng tốc phần cứng GPU để xử lý ảnh siêu tốc.
- **Office OpenXML Relationship Engine** tự động cập nhật liên kết `.rels` và `[Content_Types].xml`.

---

© 2026 Chauphan708. Mã nguồn mở phục vụ cộng đồng giáo dục và văn phòng.
