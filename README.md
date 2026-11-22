# BỘ HỌC LIỆU DẠY HỌC - BÀI 12: TẠO BIỂU MẪU (TIN HỌC 12 - KNTT)

> **Môn học**: Tin học 12 (Định hướng Tin học ứng dụng)  
> **Bộ sách**: Kết nối tri thức với cuộc sống  
> **Thời lượng**: 2 tiết (Dạy tại Phòng máy tính)  
> **Đơn vị**: Trường THPT Nguyễn Chí Thanh - Tổ Tin học  

---

## 📌 GIỚI THIỆU TỔNG QUAN

Kho lưu trữ chứa đầy đủ Kế hoạch bài dạy (Giáo án) và trọn bộ **9 học liệu dạy học chuẩn hóa** phục vụ cho **Bài 12: Tạo biểu mẫu** theo đúng tiến trình dạy học tích cực, kết hợp trò chơi học tập tương tác, kiểm thử mã nguồn và ứng dụng AI có trách nhiệm.

Tất cả học liệu văn bản đều có cả 2 định dạng:
- **`.docx`**: Định dạng Microsoft Word chuẩn OpenXML, có thể chỉnh sửa tùy biến theo tình hình thực tế lớp học.
- **`.pdf`**: Định dạng in ấn chuẩn trang A4/A5 (không bị tràn trang, căn lề và định dạng chuẩn mực sẵn sàng in phát cho học sinh).
- **`.html`**: Ứng dụng web tương tác trực tiếp chạy offline trên trình duyệt không cần cài đặt máy chủ phức tạp.

---

## 🗂 CẤU TRÚC THƯ MỤC VÀ DANH MỤC 9 HỌC LIỆU

```text
├── KHBD Bài 12.pdf                                    # Kế hoạch bài dạy chuẩn mực
└── Hoc_lieu_Bai_12/
    ├── 00_Mo_hoc_lieu_Bai_12.html                     # Bảng điều khiển (Dashboard) mở nhanh toàn bộ học liệu
    │
    ├── 01_Phieu_hoc_tap_so_1/                         # [Học liệu 1] Dùng cho HĐ 2.1 & HĐ 2.2
    │   ├── Phieu_hoc_tap_so_1.docx
    │   ├── Phieu_hoc_tap_so_1.pdf                     # Đúng chuẩn 1 trang A4
    │   └── Phieu_hoc_tap_so_1_Dap_an_GV.pdf           # Đáp án chi tiết dành cho Giáo viên
    │
    ├── 02_Tro_choi_Dau_truong_Bieu_mau/               # [Học liệu 2] Dùng cho HĐ 3.1
    │   ├── Dau_truong_Bieu_mau.html                   # Game web tương tác 4 đội, đếm ngược 20s, ngôi sao hy vọng
    │   ├── The_le_va_Bo_cau_hoi_Dau_truong_Bieu_mau.docx
    │   └── The_le_va_Bo_cau_hoi_Dau_truong_Bieu_mau.pdf
    │
    ├── 03_Bang_kiem_ma_AI_goi_y/                      # [Học liệu 3] Dùng cho HĐ 3.2
    │   ├── Bang_kiem_ma_AI_goi_y.docx
    │   └── Bang_kiem_ma_AI_goi_y.pdf                  # 5 tiêu chí kiểm thử mã HTML do AI sinh ra
    │
    ├── 04_Doan_ma_mau_co_loi/                         # [Học liệu 4] Phương án dự phòng HĐ 3.2
    │   ├── doan_ma_mau_co_loi.html                    # File HTML cài sẵn 5 lỗi điển hình
    │   ├── doan_ma_mau_da_sua_GV.html                 # Bản sửa chuẩn dành cho GV đối chiếu
    │   ├── Phieu_Doan_ma_mau_co_loi.docx
    │   ├── Phieu_Doan_ma_mau_co_loi.pdf               # Mã nguồn đánh số dòng 1 - 29
    │   └── Dap_an_5_loi_GV.pdf                        # Phân tích nguyên nhân và cách sửa 5 lỗi
    │
    ├── 05_Bang_tieu_chi_danh_gia/                     # [Học liệu 5] Dùng cho HĐ 3.2 & HĐ 4
    │   ├── Bang_tieu_chi_danh_gia_san_pham.docx
    │   └── Bang_tieu_chi_danh_gia_san_pham.pdf        # Rubric thang 10 điểm (2-3-2-2-1)
    │
    ├── 06_Phieu_nhat_ki_su_dung_AI/                   # [Học liệu 6] Dùng cho HĐ 3.2 & HĐ 4
    │   ├── Phieu_nhat_ki_su_dung_AI.docx
    │   └── Phieu_nhat_ki_su_dung_AI.pdf               # Ghi chép câu lệnh Prompt, phản biện và cam kết liêm chính
    │
    ├── 07_Bai_trinh_chieu/                            # [Học liệu 7] Slide 16:9 hỗ trợ giảng dạy
    │   ├── Bai_12_Tao_bieu_mau.pptx                   # Slide PowerPoint widescreen 16:9 có ghi chú giảng dạy
    │   ├── Bai_12_Tao_bieu_mau.pdf                    # Bản trình chiếu PDF
    │   └── hinh_anh_mo_dau/                           # 3 ảnh mockup trực quan HĐ Mở đầu
    │       ├── 01_trang_dang_ki_tai_khoan.png
    │       ├── 02_trang_dat_hang_truc_tuyen.png
    │       └── 03_phieu_khao_sat_truc_tuyen.png
    │
    ├── 08_Tep_HTML_vi_du_minh_hoa/                    # [Học liệu 8] Tệp demo giáo viên chạy trên lớp
    │   ├── 01_HD21_Vi_du_GET.html                     # Demo method="GET" (thấy rõ tham số URL)
    │   ├── 02_HD21_Vi_du_POST.html                    # Demo method="POST" (dữ liệu gửi ẩn trong Body)
    │   ├── 03_HD21_Mo_phong_GET_va_POST_Offline.html  # Mô phỏng gói tin HTTP offline trực quan
    │   ├── 04_HD22_Vi_du_tong_hop.html                # Form tổng hợp text, password, radio, checkbox, select...
    │   ├── 05_HD22_Minh_hoa_3_loi_thuong_gap.html     # Minh họa 3 lỗi học sinh hay mắc
    │   ├── ket_qua_offline.html                       # Đích nhận dữ liệu cho form offline
    │   └── tham_khao_san_pham_HS/                     # Bộ sản phẩm mẫu tham khảo cho HS thực hành
    │       ├── nv1_monan.html
    │       ├── nv2_dangkithi.html
    │       ├── dangki_clb.html
    │       └── bai11_nhung_iframe.html
    │
    └── 09_Bo_the_ABCD_4_doi/                          # [Học liệu 9] Thẻ đáp án in cho 4 đội thi
        ├── Bo_the_ABCD_4_doi.docx
        └── Bo_the_ABCD_4_doi.pdf                      # Khổ in 8 trang A4 (cắt thành 16 thẻ A5 hai mặt)
```

---

## 🚀 HƯỚNG DẪN SỬ DỤNG NHANH TRÊN LỚP HỌC

1. **Khởi động tiết dạy**:
   - Nhấp đúp mở file `Hoc_lieu_Bai_12/00_Mo_hoc_lieu_Bai_12.html` trên trình duyệt (Chrome, Edge, Cốc Cốc, Firefox).
   - Trang điều khiển cung cấp menu truy cập 1-chạm đến toàn bộ file Word, PDF, Slide và mã nguồn HTML ví dụ.
2. **Hoạt động 1 (Khởi động)**:
   - Chiếu Slide 16:9 (`07_Bai_trinh_chieu`) với 3 ảnh mockup chân thực để tạo hứng thú và định hướng vấn đề.
3. **Hoạt động 2 (Hình thành kiến thức mới)**:
   - Phát **Phiếu học tập số 1** (hoặc chiếu PDF) cho học sinh hoàn thiện mục 1 (Cấu trúc form) và mục 2 (Các điều khiển nhập liệu).
   - GV mở các tệp HTML `01_HD21_Vi_du_GET.html`, `02_HD21_Vi_du_POST.html` và `04_HD22_Vi_du_tong_hop.html` chạy thử trên trình duyệt để HS quan sát thanh địa chỉ URL.
4. **Hoạt động 3.1 (Luyện tập trắc nghiệm tương tác)**:
   - Mở file `02_Tro_choi_Dau_truong_Bieu_mau/Dau_truong_Bieu_mau.html`.
   - Phát **Bộ thẻ A, B, C, D** cho 4 đội học sinh.
   - Trò chơi có bộ đếm thời gian 20 giây mỗi câu, tự động chấm điểm, tính năng Ngôi sao hi vọng x2 điểm và bảng tổng kết vinh danh đội chiến thắng.
5. **Hoạt động 3.2 & 4 (Luyện tập thực hành & Ứng dụng AI)**:
   - HS sử dụng AI (ChatGPT, Gemini, Claude, Copilot) hỗ trợ sinh mã HTML theo yêu cầu.
   - HS tự rà soát và đánh giá mã nguồn bằng **Bảng kiểm mã do AI gợi ý** (5 tiêu chí).
   - HS ghi lại tiến trình sử dụng AI vào **Phiếu nhật kí sử dụng AI** nhằm nâng cao ý thức liêm chính học thuật.
   - Nếu phòng máy mất mạng hoặc AI bị lỗi: GV chuyển sang phương án dự phòng, phát file **Đoạn mã mẫu có lỗi cài sẵn** (`04_Doan_ma_mau_co_loi`) để HS tìm và sửa 5 lỗi.
   - Đánh giá sản phẩm theo **Bảng tiêu chí đánh giá sản phẩm thực hành** (thang 10 điểm).

---

## 📜 BẢN QUYỀN VÀ GIẤY PHÉP
Bộ học liệu được biên soạn phục vụ công tác giảng dạy Tin học 12 tại trường phổ thông, phi thương mại. Thầy cô giáo và học sinh được toàn quyền sử dụng, chia sẻ và tinh chỉnh cho phù hợp với chương trình nhà trường.
