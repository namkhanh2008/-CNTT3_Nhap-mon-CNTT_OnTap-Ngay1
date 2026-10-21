# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** tạ đình nam khánh
- **Lớp:** CNTT3
- **Link repository:** https://github.com/namkhanh2008/-CNTT3_Nhap-mon-CNTT_OnTap-Ngay1
- **Hệ điều hành (Windows/macOS):** windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```powershell
PS C:\starter-kit> pwd
PS C:\starter-kit> Get-ChildItem .\trung-tam-tieng-anh -Force
PS C:\starter-kit> cd .\trung-tam-tieng-anh
PS C:\starter-kit\trung-tam-tieng-anh> mv ".\lich_hoc.txt" ".\docs"
PS C:\starter-kit\trung-tam-tieng-anh> mv .\logo_trung_tam.PNG , .\anh_lop_hoc.JPG ".\media"
PS C:\starter-kit\trung-tam-tieng-anh> cp ".\media\logo_trung_tam.PNG" ".\archive"
PS C:\starter-kit\trung-tam-tieng-anh> rm .\temp_202.tmp
PS C:\starter-kit\trung-tam-tieng-anh> rm .\temp_201.tmp
PS C:\starter-kit\trung-tam-tieng-anh> cd logs
PS C:\starter-kit\trung-tam-tieng-anh\logs> Get-Content .\access.log
PS C:\starter-kit\trung-tam-tieng-anh\docs> ..\media\anh_lop_hoc.JPG ..\archive
PS C:\starter-kit\trung-tam-tieng-anh\docs> cd..
PS C:\starter-kit\trung-tam-tieng-anh> ls -Recurse -Force
```

### Kết quả B1 (pwd)

```text
Path
----
C:\starter-kit

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
  Directory: C:\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   7:50 PM                archive
d-----        10/20/2026   7:34 PM                data
d-----        10/20/2026   7:48 PM                docs
d-----        10/20/2026   7:34 PM                logs
d-----        10/20/2026   7:49 PM                media
-a----        10/20/2026   6:28 PM             83 .env
-a----        10/20/2026   6:28 PM            902 bai_lam_ngay1.md


    Directory: C:\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   6:28 PM           5184 logo_trung_tam.PNG


    Directory: C:\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   6:28 PM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   6:28 PM             67 lich_hoc.txt


    Directory: C:\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   6:28 PM           1072 access.log


    Directory: C:\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   6:28 PM          13559 anh_lop_hoc.JPG
-a----        10/20/2026   6:28 PM           5184 logo_trung_tam.PNG
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** /100
- **Lỗi mình đã mắc và cách sửa:**
