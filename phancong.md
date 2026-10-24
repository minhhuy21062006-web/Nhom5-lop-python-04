# PHÂN CÔNG NHIỆM VỤ – NHÓM 5 – LỚP PYTHON 04

**Đề tài:** Ứng dụng Quản lý Ký túc xá (Python + Tkinter, lập trình hướng đối tượng, lưu dữ liệu JSON)
**Repo:** Nhom5-lop-python-04

## 1. Danh sách thành viên

| STT | Họ và tên | MSSV | GitHub username | Vai trò |
|---|---|---|---|---|
| 1 | Trần Minh Huy | 2044240115 | minhhuy21062006-web | Nhóm trưởng |
| 2 | Đinh Thị Bích Phương | 2044240272 | phuongdinh040106-prog | Thành viên |
| 3 | Nguyễn Bá Đạt | 2044240056 | nguyenbadat21022006-cmyk | Thành viên |
| 4 | Nguyễn Thị Minh Ngọc | 2044240207 | ntmn144200-hub | Thành viên |

## 2. Phân công viết class và commit file

| Thành viên | Các class phụ trách | File commit |
|---|---|---|
| **1 – Trần Minh Huy (Nhóm trưởng)** | `ThucThe` (lớp cha), `ToaNha`, `Phong` (lớp trừu tượng) và các lớp con `PhongThuong`, `PhongDieuHoa`, `PhongDichVu`, `SinhVien`, `HopDong`, `HoaDon`, `ViPham`, `NguoiDung`, `TaiSan` (đóng gói, kế thừa, đa hình) | `mo_hinh/thuc_the.py`, `mo_hinh/__init__.py`, `cau_hinh.py`, `main.py`, `README.md` |
| **2 – Đinh Thị Bích Phương** | `LoiKTX`, `LoiDuLieu`, `LoiNghiepVu`, `LoiLuuTru`, `LoiXacThuc` (ngoại lệ); `LuuTruJson`, `QuanLySaoLuu`, `NhatKyHoatDong` (lưu trữ JSON, sao lưu, nhật ký); `QuanLyTaiKhoan` (xác thực); `HeThongKTX`; các hàm kiểm tra dữ liệu bằng Regex | `nghiep_vu/loi.py`, `nghiep_vu/kiem_tra.py`, `nghiep_vu/luu_tru.py`, `nghiep_vu/xac_thuc.py`, `nghiep_vu/he_thong.py`, `nghiep_vu/__init__.py` |
| **3 – Nguyễn Bá Đạt** | `QuanLyCoSo` (lớp cha), `QuanLyToaNha`, `QuanLyPhong`, `QuanLySinhVien`, `QuanLyHopDong`, `QuanLyHoaDon`, `QuanLyViPham`, `QuanLyTaiSan`; `DichVuThoiTiet`, `LoiThoiTiet`; thống kê, xuất file CSV/PDF/TXT, dữ liệu mẫu | `nghiep_vu/cac_quan_ly.py`, `nghiep_vu/thong_ke.py`, `nghiep_vu/xuat_file.py`, `nghiep_vu/api_thoi_tiet.py`, `nghiep_vu/du_lieu_mau.py`, `nghiep_vu/tien_ich_sys.py` |
| **4 – Nguyễn Thị Minh Ngọc** | Giao diện Tkinter: `UngDung`, `KhungDangNhap`, `HopThoaiNhap`, `HopThoaiChon`, `TabQuanLy` và các tab `TabToaNha`, `TabPhong`, `TabSinhVien`, `TabHopDong`, `TabHoaDon`, `TabViPham`, `TabTaiSan`, `TabTaiKhoan`, các tab xem (`TabTongQuan`, `TabSoDoTang`, `TabThongKe`, `TabThoiTiet`, `TabHoSoCuaToi`…) và các widget (`BangSapXep`, `OChonNgay`, `KhungNhapLieu`, `ThePhong`, `SoDoTang`, `BieuDoCot`, `BieuDoVong`…) | `giao_dien/ung_dung.py`, `giao_dien/dang_nhap.py`, `giao_dien/hop_thoai.py`, `giao_dien/kieu_dang.py`, `giao_dien/thanh_phan.py`, `giao_dien/tab_co_so.py`, `giao_dien/tab_quan_ly.py`, `giao_dien/tab_xem.py`, `giao_dien/__init__.py` |

## 3. Nhiệm vụ chung (cả nhóm)

| Nội dung | Người phụ trách | File commit |
|---|---|---|
| Dữ liệu mẫu JSON | Nguyễn Bá Đạt | `data/*.json` |
| Kiểm thử (41 ca unittest) | Đinh Thị Bích Phương | `tests/test_nghiep_vu.py`, `tests/__init__.py`, `chay_kiem_thu.py` |
| Báo cáo, trình chiếu, sơ đồ lớp | Nguyễn Thị Minh Ngọc | `docs/*` |
| Đóng gói file thực thi | Trần Minh Huy | `build_exe.bat`, `build_exe.sh` |
| Tạo repo, add thành viên, file phân công, `link.txt` | Trần Minh Huy | `phancong.md` |

## 4. Quy ước làm việc

- Mỗi thành viên chỉ sửa và commit các file được phân công ở trên để tránh xung đột.
- Nội dung commit message viết rõ ràng, ví dụ: `Thêm class Phong và các lớp con`.
- Trước khi `git push`, chạy `git pull` để cập nhật bản mới nhất.
- Cấu trúc thư mục giữ nguyên như dự án gốc (`mo_hinh/`, `nghiep_vu/`, `giao_dien/`, `data/`, `tests/`, `docs/`).
