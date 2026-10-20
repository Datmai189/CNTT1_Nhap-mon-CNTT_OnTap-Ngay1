# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Mai Quốc Đạt
- **Lớp:** CNTT1
- **Link repository:** https://github.com/Datmai189/CNTT1_Nhap-mon-CNTT_OnTap-Ngay1
- **Hệ điều hành (Windows/macOS):** macOS

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
pwd
ls -a
mv lich_hoc.txt docs/
mv logo_trung_tam.PNG media/
mv anh_lop_hoc.JPG media/
cp media/logo_trung_tam.PNG archive/
rm temp_201.tmp
rm temp_202.tmp
cd logs
ls -a
cd ..
cd docs
cp ../media/anh_lop_hoc.JPG ../archive/
cd ..
```

### Kết quả B1 (pwd)

```
/Users/datmei/Downloads/starter-kit/trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
.			.DS_Store		archive			data			logs
..			.env			bai_lam_ngay1.md	docs			media

./archive:
.			..			anh_lop_hoc.JPG		logo_trung_tam.PNG

./data:
.			..			hoc_vien_khoa_3.xlsx

./docs:
.		..		lich_hoc.txt

./logs:
.		..		access.log

./media:
.			..			anh_lop_hoc.JPG		logo_trung_tam.PNG

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
