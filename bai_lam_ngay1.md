# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:**
- **Lớp:**
- **Link repository:**
- **Hệ điều hành (Windows/macOS):**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
pwd
Get-ChildItem -Force
mv lich_hoc.txt docs/
mv logo_trung_tam.png media/
mv anh_lop_hoc.jpg media/
cp media/logo_trung_tam.png archive/
rm temp_201.tmp
rm temp_202.tmp
cd logs
ls
cd ..
cd docs
cp ../media/anh_lop_hoc.jpg ../archive/
cd ..
Get-ChildItem -Recurse -Force

```

### Kết quả B1 (pwd)

```text
1.
Path
----
D:\

2.
    Directory: D:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d--hs-         6/14/2025   3:37 PM                $RECYCLE.BIN
d-----         10/6/2026   2:00 PM                index.txt
d-----         10/6/2026   1:58 PM                khanh
d-----        10/14/2026  10:24 AM                khanh-nam
d-----         4/15/2026  12:05 PM                Kênh 1
d-----         4/15/2026   3:49 PM                Kênh 2
d-----        12/22/2025  10:20 PM                Medal
d-----         4/13/2026  11:55 AM                mp3tag-v3.33.1-x64-setup.exe
d-----         4/13/2026  11:55 AM                mp3tag-v3.34-x64-setup
d-----         10/6/2026   1:58 PM                nam
d-----         10/6/2026   1:58 PM                nam,khnh
d-----         10/6/2026   2:15 PM                nhacdeghep
d--hs-         8/12/2025   9:33 AM                Recovery
d--hs-        10/16/2026  12:49 PM                System Volume Information
d-----        10/13/2026   2:49 PM                Thư mục mới
-a----        10/14/2026  11:38 AM             44 auto_report.txt
-a----         7/11/2026  12:03 PM          37589 Bao_cao_PTIT_Rikkeisoft.docx
-a----        10/14/2026  11:59 AM          16509 bài tổng hợp.docx
-a----         4/11/2026  10:49 AM        2879000 CapCut_7627343393055588369_installer.exe
-a----         7/11/2026  11:35 AM        1436704 ChatGPT Installer (1).exe
-a----         7/11/2026  11:35 AM        1436704 ChatGPT Installer.exe
-a----        10/13/2026   2:29 PM           4730 check_log.txt
-a----         8/30/2026   7:48 PM       59437056 Cloudflare_WARP_2026.7.1376.0 (1).msi
-a----         8/30/2026  12:47 PM       59437056 Cloudflare_WARP_2026.7.1376.0.msi
-a----         8/30/2026   7:47 PM       58869006 Cloudflare_WARP_2026.7.1376.0.zip
-a----         5/22/2026  10:39 PM      133795936 GeoGebraCalculator-Windows-Installer-6-0-920-0.exe
-a----        10/13/2026   1:51 PM        4038306 hope.log
-a----         8/31/2026  10:23 AM       84586594 IsleVOIP-Setup.exe
-a----         8/30/2026  10:31 PM        1986053 Không được xác nhận 516334.crdownload
-a----         8/30/2026  10:37 PM        6498959 Không được xác nhận 78728.crdownload
-a----         8/31/2026  12:22 PM        4415824 LagoFastInstaller_platformid1_aid1788148911730593_win (1).exe
-a----         8/31/2026  11:02 AM        4415824 LagoFastInstaller_platformid1_aid1788148911730593_win.exe
-a----         9/23/2026   8:12 AM      426636536 Lark-win32_x64-8.0.3-signed.exe
-a----        10/14/2026  11:34 AM             44 logs
-a----         4/19/2026  10:10 AM           4608 Microsoft.Services.Store.winmd
-a----         4/13/2026  11:54 AM        5296858 mp3tag-v3.33.1-x64-setup.exe.zip
-a----         4/13/2026  11:14 AM        5912025 mp3tag-v3.34-x64-setup.rar
-a----         10/6/2026   2:04 PM              0 namkhanh
-a----        10/14/2026  11:38 AM            219 New Text Document (2).txt
-a----        10/13/2026   2:49 PM              0 New Text Document.txt
-a----         4/24/2026   8:43 PM       29143512 python-3.13.13-amd64.exe
-a----         9/23/2026   2:23 PM           4235 report.recipe.md
-a----        10/13/2026   2:09 PM           4730 report.txt
-a----         9/21/2026   8:43 PM       13525968 RobloxPlayerInstaller (1).exe
-a----         6/29/2026  10:34 PM       10106320 RobloxPlayerInstaller.exe
-a----        10/13/2026   2:29 PM           3366 takhanhnamdinh.com
-a----        10/13/2026   2:34 PM          22632 takhanhnamdinh.txt
-a----         8/31/2026  10:48 AM        3599808 WGBSetup_1.5.7.81.exe
-a----         4/14/2026   6:39 PM        5784568 wps_wid.cid-1832157835.1776166769.exe

3.
PS D:\> mv lich_hoc.txt docs/
PS D:\>
PS D:\> mv logo_trung_tam.png media/
PS D:\>
PS D:\> mv anh_lop_hoc.jpg media/
PS D:\>
4.

PS D:\> cp media/logo_trung_tam.png archive/
PS D:\>
5.
PS D:\> rm temp_201.tmp
PS D:\>
PS D:\> rm temp_202.tmp
PS D:\>
6.
PS D:\> rm logs
PS D:\> cd logs
PS D:\logs> ls
PS D:\logs> cd ..
PS D:\>
7.
PS D:\> cd docs
PS D:\docs> cp ../media/anh_lop_hoc.jpg ../archive/
PS D:\docs> cd ..
PS D:\>
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
PS D:\> Get-ChildItem -Recurse -Force


    Directory: D:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d--hs-         6/14/2025   3:37 PM                $RECYCLE.BIN
d-----        10/20/2026  11:36 AM                archive
d-----        10/20/2026  11:27 AM                docs
d-----         10/6/2026   2:00 PM                index.txt
d-----         10/6/2026   1:58 PM                khanh
d-----        10/14/2026  10:24 AM                khanh-nam
d-----         4/15/2026  12:05 PM                Kênh 1
d-----         4/15/2026   3:49 PM                Kênh 2
d-----        10/20/2026  11:44 AM                logs
d-----        12/22/2025  10:20 PM                Medal
d-----        10/20/2026  11:26 AM                media
d-----         4/13/2026  11:55 AM                mp3tag-v3.33.1-x64-setup.exe
d-----         4/13/2026  11:55 AM                mp3tag-v3.34-x64-setup
d-----         10/6/2026   1:58 PM                nam
d-----         10/6/2026   1:58 PM                nam,khnh
d-----         10/6/2026   2:15 PM                nhacdeghep
d--hs-         8/12/2025   9:33 AM                Recovery
d--hs-        10/16/2026  12:49 PM                System Volume Information
d-----        10/13/2026   2:49 PM                Thư mục mới
-a----        10/14/2026  11:38 AM             44 auto_report.txt
-a----         7/11/2026  12:03 PM          37589 Bao_cao_PTIT_Rikkeisoft.docx
-a----        10/14/2026  11:59 AM          16509 bài tổng hợp.docx
-a----         4/11/2026  10:49 AM        2879000 CapCut_7627343393055588369_installer.exe
-a----         7/11/2026  11:35 AM        1436704 ChatGPT Installer (1).exe
-a----         7/11/2026  11:35 AM        1436704 ChatGPT Installer.exe
-a----        10/13/2026   2:29 PM           4730 check_log.txt
-a----         8/30/2026   7:48 PM       59437056 Cloudflare_WARP_2026.7.1376.0 (1).msi
-a----         8/30/2026  12:47 PM       59437056 Cloudflare_WARP_2026.7.1376.0.msi
-a----         8/30/2026   7:47 PM       58869006 Cloudflare_WARP_2026.7.1376.0.zip
-a----         5/22/2026  10:39 PM      133795936 GeoGebraCalculator-Windows-Installer-6-0-920-0.exe
-a----        10/13/2026   1:51 PM        4038306 hope.log
-a----         8/31/2026  10:23 AM       84586594 IsleVOIP-Setup.exe
-a----         8/30/2026  10:31 PM        1986053 Không được xác nhận 516334.crdownload
-a----         8/30/2026  10:37 PM        6498959 Không được xác nhận 78728.crdownload
-a----         8/31/2026  12:22 PM        4415824 LagoFastInstaller_platformid1_aid1788148911730593_win (1).exe
-a----         8/31/2026  11:02 AM        4415824 LagoFastInstaller_platformid1_aid1788148911730593_win.exe
-a----         9/23/2026   8:12 AM      426636536 Lark-win32_x64-8.0.3-signed.exe
-a----        10/20/2026  11:25 AM              0 lich_hoc.txt
-a----        10/20/2026  11:23 AM              0 logo_trung_tam.png
-a----         4/19/2026  10:10 AM           4608 Microsoft.Services.Store.winmd
-a----         4/13/2026  11:54 AM        5296858 mp3tag-v3.33.1-x64-setup.exe.zip
-a----         4/13/2026  11:14 AM        5912025 mp3tag-v3.34-x64-setup.rar
-a----         10/6/2026   2:04 PM              0 namkhanh
-a----        10/14/2026  11:38 AM            219 New Text Document (2).txt
-a----        10/20/2026  11:36 AM              0 New Text Document (3).txt
-a----        10/13/2026   2:49 PM              0 New Text Document.txt
-a----         4/24/2026   8:43 PM       29143512 python-3.13.13-amd64.exe
-a----         9/23/2026   2:23 PM           4235 report.recipe.md
-a----        10/13/2026   2:09 PM           4730 report.txt
-a----         9/21/2026   8:43 PM       13525968 RobloxPlayerInstaller (1).exe
-a----         6/29/2026  10:34 PM       10106320 RobloxPlayerInstaller.exe
-a----        10/13/2026   2:29 PM           3366 takhanhnamdinh.com
-a----        10/13/2026   2:34 PM          22632 takhanhnamdinh.txt
-a----         8/31/2026  10:48 AM        3599808 WGBSetup_1.5.7.81.exe
-a----         4/14/2026   6:39 PM        5784568 wps_wid.cid-1832157835.1776166769.exe


    Directory: D:\$RECYCLE.BIN


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d--hs-        10/20/2026  11:27 AM                S-1-5-21-1462887836-2664994733-3090533349-1002


    Directory: D:\$RECYCLE.BIN\S-1-5-21-1462887836-2664994733-3090533349-1002


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         10/5/2026   1:35 PM            118 $I0XJM8W.mp3
-a----         10/5/2026   1:36 PM            196 $I13KDMO.docx
-a----         10/6/2026  11:13 AM            180 $I4WY3KM.mp3
-a----         10/5/2026   1:35 PM             90 $I5HE0AZ.mp3
-a----         10/5/2026   1:35 PM             92 $I632IZB.pdf
-a----         10/5/2026   1:34 PM             48 $I90RG7T.pdf
-a----         10/5/2026   1:35 PM            104 $IBJ0RKI.pdf
-a----         10/5/2026   1:36 PM            122 $IBYT0LC.png
-a----         10/5/2026   1:35 PM             52 $ID61E3I.pdf
-a----         10/5/2026   1:35 PM             56 $IF8QH16.pdf
-a----         10/5/2026   1:35 PM            102 $IG01LLG.exe
-a----         10/5/2026   1:35 PM            100 $IGL3QI1.pdf
-a----         10/5/2026   1:35 PM            114 $IH70FZA.pdf
-a----         10/5/2026   1:34 PM             48 $IIZZ9N6.pdf
-a----         10/5/2026   1:35 PM             52 $IJYAGQ5.pdf
-a----         10/5/2026   1:36 PM            212 $ILBU90I.docx
-a----         10/5/2026   1:34 PM            122 $ILOHCTD.pdf
-a----         10/5/2026   1:34 PM             48 $IQYDSMR.pdf
-a----         10/5/2026   1:35 PM            112 $IQYDZI6.mp3
-a----         10/5/2026   1:34 PM             54 $IRE0VL9.pdf
-a----         10/5/2026   1:36 PM            204 $IRUA3E4.docx
-a----         10/5/2026   1:34 PM            206 $ISC0TUC.pdf
-a----         10/5/2026   1:34 PM            160 $ITK9FVB.mp3
-a----         10/5/2026   1:35 PM            130 $IXW1BZU.docx
-a----         10/5/2026   1:35 PM            142 $IY1MV30.exe
-a----        10/13/2026   2:51 PM             82 $IZ4XFGR.txt
-a----        10/20/2026  11:27 AM             70 $IZWBLGW.txt
-a----          9/8/2026  11:12 PM         315488 $R0XJM8W.mp3
-a----         4/14/2026   5:34 PM          23936 $R13KDMO.docx
-a----          9/8/2026  11:16 PM         492292 $R4WY3KM.mp3
-a----          9/8/2026  11:10 PM          52269 $R5HE0AZ.mp3
-a----         4/19/2026  10:59 AM         126215 $R632IZB.pdf
-a----         5/31/2026   6:17 PM          46802 $R90RG7T.pdf
-a----          7/5/2026  10:00 AM         216712 $RBJ0RKI.pdf
-a----         9/23/2026   2:07 PM        1466083 $RBYT0LC.png
-a----         5/31/2026   7:24 PM         121013 $RD61E3I.pdf
-a----         5/31/2026   6:17 PM          22623 $RF8QH16.pdf
-a----         9/18/2026  11:33 PM       75831040 $RG01LLG.exe
-a----         4/24/2026   5:54 PM         125937 $RGL3QI1.pdf
-a----          7/5/2026  10:05 AM        2484319 $RH70FZA.pdf
-a----         5/31/2026   6:17 PM          43712 $RIZZ9N6.pdf
-a----         5/31/2026   7:17 PM         225585 $RJYAGQ5.pdf
-a----         4/14/2026   6:36 PM          23444 $RLBU90I.docx
-a----         4/14/2026   1:04 PM          37442 $RLOHCTD.pdf
-a----         5/31/2026   6:16 PM         405016 $RQYDSMR.pdf
-a----          9/8/2026  11:14 PM         660447 $RQYDZI6.mp3
-a----         5/31/2026   7:18 PM         134801 $RRE0VL9.pdf
-a----         4/14/2026   6:32 PM          23444 $RRUA3E4.docx
-a----         4/26/2026  10:16 PM       19492350 $RSC0TUC.pdf
-a----          9/8/2026  11:15 PM          92986 $RTK9FVB.mp3
-a----         4/14/2026  11:36 AM          87195 $RXW1BZU.docx
-a----         7/25/2026   7:35 PM        3527656 $RY1MV30.exe
-a----        10/13/2026   2:42 PM              0 $RZ4XFGR.txt
-a----        10/20/2026  11:17 AM              0 $RZWBLGW.txt
-a-hs-         6/14/2025   3:37 PM            129 desktop.ini


    Directory: D:\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  11:22 AM              0 anh_lop_hoc.jpg
-a----        10/20/2026  11:23 AM              0 logo_trung_tam.png


    Directory: D:\khanh-nam


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/14/2026   3:39 PM                labterminal
d-----         10/8/2026   1:23 PM                nam-khanh
d-----         10/8/2026   1:18 PM                namkhanh
-a----        10/13/2026   2:56 PM           1086 check_meme_auto.ps1 - Lối tắt.lnk
-a----        10/13/2026   2:51 PM              0 check_meme_auto.ps1.txt
-a----        10/13/2026   3:02 PM              0 kkkkkkk.ps1.txt


    Directory: D:\khanh-nam\labterminal


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/14/2026  10:37 AM                backup
d-----        10/14/2026  11:03 AM                logs
d-----        10/14/2026  10:45 AM                reports
-a----        10/14/2026   3:44 PM            207 auto_report (2).ps1
-a----        10/14/2026  11:54 AM            220 auto_report.ps1
-a----        10/14/2026  11:58 AM            236 auto_report.txt
-a----        10/14/2026  11:23 AM            496 r.txt
-a----        10/14/2026  11:19 AM             14 t.txt


    Directory: D:\khanh-nam\labterminal\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/14/2026  10:25 AM            533 access_backup.log


    Directory: D:\khanh-nam\labterminal\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/14/2026  10:25 AM            533 access.log.txt
-a----        10/14/2026  11:04 AM              8 back_up_500.log


    Directory: D:\khanh-nam\labterminal\reports


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/14/2026  10:42 AM              0 notes.txt


    Directory: D:\khanh-nam\nam-khanh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         10/6/2026   2:54 PM                ff
d-----         10/8/2026   1:23 PM                src-hoangkimcot
d-----         10/6/2026   2:21 PM                takhanh


    Directory: D:\khanh-nam\nam-khanh\ff


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         10/6/2026   2:33 PM              0 khanh
-a----         10/6/2026   2:33 PM              0 khanh-nam
-a----         10/6/2026   2:33 PM              0 namkhanh


    Directory: D:\khanh-nam\namkhanh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         10/8/2026   1:18 PM                moinhat


    Directory: D:\Kênh 1


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         4/13/2026  12:04 PM    16402160340 432hz + 741hz-the deep healing sleep  total body restoration, emotional reset#deepsleep432hz.mp4
-a----         4/13/2026  11:52 AM            198 calming sleep music.txt
-a----         4/13/2026  12:05 PM         354318 z7720266091806_0c83cbc82154ceebd9cd1c0e466977f3.jpg


    Directory: D:\Kênh 2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         4/15/2026   3:49 PM    14150986508 432hz - fall into deep sleep in 3 minutes - support body & mind recovery, ease tension#brainfrequency.mp4
-a----         4/15/2026   3:38 PM              0 New Tài liệu văn bản.txt


    Directory: D:\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  11:22 AM              0 anh_lop_hoc.jpg
-a----        10/20/2026  11:23 AM              0 logo_trung_tam.png


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:55 AM                data
d-----         4/13/2026  11:55 AM                export
d-----         4/13/2026  11:55 AM                help
d-----         4/13/2026  11:55 AM                lang
------         4/11/2026   9:13 AM        5296688 mp3tag-v3.33.1-x64-setup.exe
-a----          2/6/2026   6:05 PM       13235296 Mp3tag.exe
-a----         4/13/2026  11:55 AM             68 Mp3tagSetup.ini
-a----          2/6/2026   6:05 PM         501352 Mp3tagShell.dll
-a----          2/6/2026   6:05 PM         161035 Mp3tagShell.msix
-a----         4/13/2026  11:55 AM         180512 Mp3tagUninstall.exe
-a----          2/6/2026   6:05 PM         199225 Mp3tagVersion.txt


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:55 AM                actions
d-----         4/13/2026  11:55 AM                sources
-a----          2/6/2026   6:05 PM            570 empty.mte
-a----          2/6/2026   6:05 PM            325 freedb.src


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\data\actions


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          2/6/2026   6:05 PM             33 Case conversion.mta
-a----          2/6/2026   6:05 PM            827 CD-R.mta
-a----          2/6/2026   6:05 PM            230 Standard.mta


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\data\sources


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          2/6/2026   6:05 PM            710 Cover Art#Discogs Artist + Album.src
-a----          2/6/2026   6:05 PM            783 Cover Art#Discogs Artist + Title.src
-a----          2/6/2026   6:05 PM            698 Cover Art#Discogs Artist + Year.src
-a----          2/6/2026   6:05 PM           1849 Cover Art#Discogs Release ID.src
-a----          2/6/2026   6:05 PM           3982 Cover Art#Discogs.inc
-a----          2/6/2026   6:05 PM            564 Cover Art#Discogs.src
-a----          2/6/2026   6:05 PM           3658 Cover Art#MusicBrainz.src
-a----          2/6/2026   6:05 PM            685 Discogs Artist + Album.src
-a----          2/6/2026   6:05 PM            758 Discogs Artist + Title.src
-a----          2/6/2026   6:05 PM            673 Discogs Artist + Year.src
-a----          2/6/2026   6:05 PM          15518 Discogs Release ID.src
-a----          2/6/2026   6:05 PM          17907 Discogs.inc
-a----          2/6/2026   6:05 PM            539 Discogs.src
-a----          2/6/2026   6:05 PM           9090 MusicBrainz.src


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\export


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          2/6/2026   6:05 PM            327 csv.mte
-a----          2/6/2026   6:05 PM           2052 html_mp3tag.mte
-a----          2/6/2026   6:05 PM           2046 html_standard.mte
-a----          2/6/2026   6:05 PM            523 RTF.mte
-a----          2/6/2026   6:05 PM            118 sfv.mte
-a----          2/6/2026   6:05 PM            127 txt_taglist.mte


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\help


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:55 AM                images
-a----          2/6/2026   6:05 PM           3123 helpmap.idx


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\help\images


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          2/6/2026   6:05 PM          39366 donate-button-120.bmp
-a----          2/6/2026   6:05 PM          56154 donate-button-144.bmp
-a----          2/6/2026   6:05 PM         100054 donate-button-192.bmp
-a----          2/6/2026   6:05 PM          25054 donate-button-96.bmp
-a----          2/6/2026   6:05 PM          39366 donate-button-de-120.bmp
-a----          2/6/2026   6:05 PM          56154 donate-button-de-144.bmp
-a----          2/6/2026   6:05 PM         100054 donate-button-de-192.bmp
-a----          2/6/2026   6:05 PM          25054 donate-button-de-96.bmp


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\lang


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:55 AM                icons
-a----          2/6/2026   6:05 PM          45739 Arabic.lng
-a----          2/6/2026   6:05 PM          51908 Armenian.lng
-a----          2/6/2026   6:05 PM          51150 Belarusian.lng
-a----          2/6/2026   6:05 PM          53207 Bulgarian.lng
-a----          2/6/2026   6:05 PM          41687 Catalan.lng
-a----          2/6/2026   6:05 PM          37499 Chinese-CN.lng
-a----          2/6/2026   6:05 PM          36731 Chinese-TW.lng
-a----          2/6/2026   6:05 PM          43267 Corsican.lng
-a----          2/6/2026   6:05 PM          37071 Croatian.lng
-a----          2/6/2026   6:05 PM          39578 Czech.lng
-a----          2/6/2026   6:05 PM          36454 Danish.lng
-a----          2/6/2026   6:05 PM          39119 Dutch.lng
-a----          2/6/2026   6:05 PM          36052 English.lng
-a----          2/6/2026   6:05 PM          47211 Farsi.lng
-a----          2/6/2026   6:05 PM          36870 Finnish.lng
-a----          2/6/2026   6:05 PM          41672 French.lng
-a----          2/6/2026   6:05 PM          39703 Galician.lng
-a----          2/6/2026   6:05 PM          40686 German.lng
-a----          2/6/2026   6:05 PM          52466 Greek.lng
-a----          2/6/2026   6:05 PM          43533 Hebrew.lng
-a----          2/6/2026   6:05 PM          41154 Hungarian.lng
-a----          2/6/2026   6:05 PM          37143 Indonesian.lng
-a----          2/6/2026   6:05 PM          40119 Italian.lng
-a----          2/6/2026   6:05 PM          48548 Japanese.lng
-a----          2/6/2026   6:05 PM          41362 Korean.lng
-a----          2/6/2026   6:05 PM          39810 Lithuanian.lng
-a----          2/6/2026   6:05 PM          50633 Macedonian.lng
-a----          2/6/2026   6:05 PM          37251 Norwegian.lng
-a----          2/6/2026   6:05 PM          39725 Polish.lng
-a----          2/6/2026   6:05 PM          40788 Portuguese-BR.lng
-a----          2/6/2026   6:05 PM          40110 Portuguese-PT.lng
-a----          2/6/2026   6:05 PM          39425 Romanian.lng
-a----          2/6/2026   6:05 PM          52788 Russian.lng
-a----          2/6/2026   6:05 PM          35838 Serbian (Latin).lng
-a----          2/6/2026   6:05 PM          46999 Serbian.lng
-a----          2/6/2026   6:05 PM          39475 Slovak.lng
-a----          2/6/2026   6:05 PM          37321 Slovenian.lng
-a----          2/6/2026   6:05 PM          41989 Spanish.lng
-a----          2/6/2026   6:05 PM          38950 Swedish.lng
-a----          2/6/2026   6:05 PM          69193 Tamil.lng
-a----          2/6/2026   6:05 PM          38637 Turkish.lng
-a----          2/6/2026   6:05 PM          53425 Ukrainian.lng
-a----          2/6/2026   6:05 PM          44617 Vietnamese.lng


    Directory: D:\mp3tag-v3.33.1-x64-setup.exe\lang\icons


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          2/6/2026   6:05 PM            894 Armenian.ico
-a----          2/6/2026   6:05 PM           1150 Belarusian.ico
-a----          2/6/2026   6:05 PM           2862 Bulgarian.ico
-a----          2/6/2026   6:05 PM           2862 Catalan.ico
-a----          2/6/2026   6:05 PM           2862 Chinese-CN.ico
-a----          2/6/2026   6:05 PM           2862 Chinese-TW.ico
-a----          2/6/2026   6:05 PM           2862 Corsican.ico
-a----          2/6/2026   6:05 PM           2862 Croatian.ico
-a----          2/6/2026   6:05 PM           2862 Czech.ico
-a----          2/6/2026   6:05 PM           1150 Danish.ico
-a----          2/6/2026   6:05 PM           2862 Dutch.ico
-a----          2/6/2026   6:05 PM           2862 English.ico
-a----          2/6/2026   6:05 PM           2862 Farsi.ico
-a----          2/6/2026   6:05 PM           2862 Finnish.ico
-a----          2/6/2026   6:05 PM           2862 French.ico
-a----          2/6/2026   6:05 PM           2862 German.ico
-a----          2/6/2026   6:05 PM           2862 Greek.ico
-a----          2/6/2026   6:05 PM           1406 Hebrew.ico
-a----          2/6/2026   6:05 PM           2862 Hungarian.ico
-a----          2/6/2026   6:05 PM           1132 Indonesian.ico
-a----          2/6/2026   6:05 PM           2862 Italian.ico
-a----          2/6/2026   6:05 PM           2862 Japanese.ico
-a----          2/6/2026   6:05 PM           2862 Korean.ico
-a----          2/6/2026   6:05 PM           1150 Lithuanian.ico
-a----          2/6/2026   6:05 PM           2862 Norwegian.ico
-a----          2/6/2026   6:05 PM           2862 Polish.ico
-a----          2/6/2026   6:05 PM           2862 Portuguese-BR.ico
-a----          2/6/2026   6:05 PM           2862 Portuguese-PT.ico
-a----          2/6/2026   6:05 PM           2862 Romanian.ico
-a----          2/6/2026   6:05 PM           2862 Russian.ico
-a----          2/6/2026   6:05 PM           2862 Serbian (Latin).ico
-a----          2/6/2026   6:05 PM           2862 Serbian.ico
-a----          2/6/2026   6:05 PM           2862 Slovak.ico
-a----          2/6/2026   6:05 PM           1150 Slovenian.ico
-a----          2/6/2026   6:05 PM           2862 Spanish.ico
-a----          2/6/2026   6:05 PM           2862 Swedish.ico
-a----          2/6/2026   6:05 PM           2862 Turkish.ico
-a----          2/6/2026   6:05 PM           1406 Ukrainian.ico
-a----          2/6/2026   6:05 PM           1406 Vietnamese.ico


    Directory: D:\mp3tag-v3.34-x64-setup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:16 AM                data
d-----         4/13/2026  11:16 AM                export
d-----         4/13/2026  11:16 AM                help
d-----         4/13/2026  11:16 AM                lang
-a----         4/11/2026   3:02 PM        5951960 mp3tag-v3.34-x64-setup.exe
-a----         4/10/2026   3:08 PM       24916072 Mp3tag.exe
-a----         4/13/2026  11:16 AM             68 Mp3tagSetup.ini
-a----         4/10/2026   3:08 PM         501344 Mp3tagShell.dll
-a----         4/10/2026   3:08 PM         161038 Mp3tagShell.msix
-a----         4/13/2026  11:16 AM         180520 Mp3tagUninstall.exe
-a----         4/10/2026   3:07 PM         202413 Mp3tagVersion.txt


    Directory: D:\mp3tag-v3.34-x64-setup\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:16 AM                actions
d-----         4/13/2026  11:16 AM                sources
-a----         4/10/2026   3:07 PM            570 empty.mte
-a----         4/10/2026   3:07 PM            325 freedb.src


    Directory: D:\mp3tag-v3.34-x64-setup\data\actions


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         4/10/2026   3:07 PM             33 Case conversion.mta
-a----         4/10/2026   3:07 PM            827 CD-R.mta
-a----         4/10/2026   3:07 PM            230 Standard.mta


    Directory: D:\mp3tag-v3.34-x64-setup\data\sources


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         4/10/2026   3:07 PM            710 Cover Art#Discogs Artist + Album.src
-a----         4/10/2026   3:07 PM            783 Cover Art#Discogs Artist + Title.src
-a----         4/10/2026   3:07 PM            698 Cover Art#Discogs Artist + Year.src
-a----         4/10/2026   3:07 PM           1849 Cover Art#Discogs Release ID.src
-a----         4/10/2026   3:07 PM           3982 Cover Art#Discogs.inc
-a----         4/10/2026   3:07 PM            564 Cover Art#Discogs.src
-a----         4/10/2026   3:07 PM           3658 Cover Art#MusicBrainz.src
-a----         4/10/2026   3:07 PM            685 Discogs Artist + Album.src
-a----         4/10/2026   3:07 PM            758 Discogs Artist + Title.src
-a----         4/10/2026   3:07 PM            673 Discogs Artist + Year.src
-a----         4/10/2026   3:07 PM          15518 Discogs Release ID.src
-a----         4/10/2026   3:07 PM          17907 Discogs.inc
-a----         4/10/2026   3:07 PM            539 Discogs.src
-a----         4/10/2026   3:07 PM           9090 MusicBrainz.src


    Directory: D:\mp3tag-v3.34-x64-setup\export


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         4/10/2026   3:07 PM            327 csv.mte
-a----         4/10/2026   3:07 PM           2052 html_mp3tag.mte
-a----         4/10/2026   3:07 PM           2046 html_standard.mte
-a----         4/10/2026   3:07 PM            523 RTF.mte
-a----         4/10/2026   3:07 PM            118 sfv.mte
-a----         4/10/2026   3:07 PM            127 txt_taglist.mte


    Directory: D:\mp3tag-v3.34-x64-setup\help


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:16 AM                images
-a----         4/10/2026   3:08 PM           3123 helpmap.idx


    Directory: D:\mp3tag-v3.34-x64-setup\help\images


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         4/10/2026   3:08 PM          39366 donate-button-120.bmp
-a----         4/10/2026   3:08 PM          56154 donate-button-144.bmp
-a----         4/10/2026   3:08 PM         100054 donate-button-192.bmp
-a----         4/10/2026   3:08 PM          25054 donate-button-96.bmp
-a----         4/10/2026   3:08 PM          39366 donate-button-de-120.bmp
-a----         4/10/2026   3:08 PM          56154 donate-button-de-144.bmp
-a----         4/10/2026   3:08 PM         100054 donate-button-de-192.bmp
-a----         4/10/2026   3:08 PM          25054 donate-button-de-96.bmp


    Directory: D:\mp3tag-v3.34-x64-setup\lang


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/13/2026  11:16 AM                icons
-a----         4/10/2026   3:07 PM          46617 Arabic.lng
-a----         4/10/2026   3:07 PM          52774 Armenian.lng
-a----         4/10/2026   3:07 PM          52020 Belarusian.lng
-a----         4/10/2026   3:07 PM          54076 Bulgarian.lng
-a----         4/10/2026   3:07 PM          42945 Catalan.lng
-a----         4/10/2026   3:07 PM          38415 Chinese-CN.lng
-a----         4/10/2026   3:07 PM          37619 Chinese-TW.lng
-a----         4/10/2026   3:07 PM          44396 Corsican.lng
-a----         4/10/2026   3:07 PM          37961 Croatian.lng
-a----         4/10/2026   3:07 PM          40474 Czech.lng
-a----         4/10/2026   3:07 PM          37342 Danish.lng
-a----         4/10/2026   3:07 PM          40004 Dutch.lng
-a----         4/10/2026   3:07 PM          36941 English.lng
-a----         4/10/2026   3:07 PM          48080 Farsi.lng
-a----         4/10/2026   3:07 PM          37752 Finnish.lng
-a----         4/10/2026   3:07 PM          42567 French.lng
-a----         4/10/2026   3:07 PM          40582 Galician.lng
-a----         4/10/2026   3:07 PM          41688 German.lng
-a----         4/10/2026   3:07 PM          53336 Greek.lng
-a----         4/10/2026   3:07 PM          44404 Hebrew.lng
-a----         4/10/2026   3:07 PM          42034 Hungarian.lng
-a----         4/10/2026   3:07 PM          38027 Indonesian.lng
-a----         4/10/2026   3:07 PM          41163 Italian.lng
-a----         4/10/2026   3:07 PM          49700 Japanese.lng
-a----         4/10/2026   3:07 PM          42242 Korean.lng
-a----         4/10/2026   3:07 PM          40678 Lithuanian.lng
-a----         4/10/2026   3:07 PM          51512 Macedonian.lng
-a----         4/10/2026   3:07 PM          38138 Norwegian.lng
-a----         4/10/2026   3:07 PM          40615 Polish.lng
-a----         4/10/2026   3:07 PM          41860 Portuguese-BR.lng
-a----         4/10/2026   3:07 PM          40995 Portuguese-PT.lng
-a----         4/10/2026   3:07 PM          40303 Romanian.lng
-a----         4/10/2026   3:07 PM          53658 Russian.lng
-a----         4/10/2026   3:07 PM          36727 Serbian (Latin).lng
-a----         4/10/2026   3:07 PM          47874 Serbian.lng
-a----         4/10/2026   3:07 PM          40482 Slovak.lng
-a----         4/10/2026   3:07 PM          38207 Slovenian.lng
-a----         4/10/2026   3:07 PM          43115 Spanish.lng
-a----         4/10/2026   3:07 PM          39839 Swedish.lng
-a----         4/10/2026   3:07 PM          70015 Tamil.lng
-a----         4/10/2026   3:07 PM          39520 Turkish.lng
-a----         4/10/2026   3:07 PM          54292 Ukrainian.lng
-a----         4/10/2026   3:07 PM          45500 Vietnamese.lng


    Directory: D:\mp3tag-v3.34-x64-setup\lang\icons


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         4/10/2026   3:07 PM            894 Armenian.ico
-a----         4/10/2026   3:07 PM           1150 Belarusian.ico
-a----         4/10/2026   3:07 PM           2862 Bulgarian.ico
-a----         4/10/2026   3:07 PM           2862 Catalan.ico
-a----         4/10/2026   3:07 PM           2862 Chinese-CN.ico
-a----         4/10/2026   3:07 PM           2862 Chinese-TW.ico
-a----         4/10/2026   3:07 PM           2862 Corsican.ico
-a----         4/10/2026   3:07 PM           2862 Croatian.ico
-a----         4/10/2026   3:07 PM           2862 Czech.ico
-a----         4/10/2026   3:07 PM           1150 Danish.ico
-a----         4/10/2026   3:07 PM           2862 Dutch.ico
-a----         4/10/2026   3:07 PM           2862 English.ico
-a----         4/10/2026   3:07 PM           2862 Farsi.ico
-a----         4/10/2026   3:07 PM           2862 Finnish.ico
-a----         4/10/2026   3:07 PM           2862 French.ico
-a----         4/10/2026   3:07 PM           2862 German.ico
-a----         4/10/2026   3:07 PM           2862 Greek.ico
-a----         4/10/2026   3:07 PM           1406 Hebrew.ico
-a----         4/10/2026   3:07 PM           2862 Hungarian.ico
-a----         4/10/2026   3:07 PM           1132 Indonesian.ico
-a----         4/10/2026   3:07 PM           2862 Italian.ico
-a----         4/10/2026   3:07 PM           2862 Japanese.ico
-a----         4/10/2026   3:07 PM           2862 Korean.ico
-a----         4/10/2026   3:07 PM           1150 Lithuanian.ico
-a----         4/10/2026   3:07 PM           2862 Norwegian.ico
-a----         4/10/2026   3:07 PM           2862 Polish.ico
-a----         4/10/2026   3:07 PM           2862 Portuguese-BR.ico
-a----         4/10/2026   3:07 PM           2862 Portuguese-PT.ico
-a----         4/10/2026   3:07 PM           2862 Romanian.ico
-a----         4/10/2026   3:07 PM           2862 Russian.ico
-a----         4/10/2026   3:07 PM           2862 Serbian (Latin).ico
-a----         4/10/2026   3:07 PM           2862 Serbian.ico
-a----         4/10/2026   3:07 PM           2862 Slovak.ico
-a----         4/10/2026   3:07 PM           1150 Slovenian.ico
-a----         4/10/2026   3:07 PM           2862 Spanish.ico
-a----         4/10/2026   3:07 PM           2862 Swedish.ico
-a----         4/10/2026   3:07 PM           2862 Turkish.ico
-a----         4/10/2026   3:07 PM           1406 Ukrainian.ico
-a----         4/10/2026   3:07 PM           1406 Vietnamese.ico


    Directory: D:\nhacdeghep


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         10/6/2026   2:19 PM                amluong


    Directory: D:\nhacdeghep\amluong


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         10/6/2026   1:57 PM                amluong2
d-----         10/6/2026   2:19 PM                khanh
d-----         10/6/2026   2:19 PM                nam
d-----         10/6/2026   2:18 PM                namkhanh


    Directory: D:\nhacdeghep\amluong\amluong2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         10/6/2026   1:57 PM                game
-a----          4/5/2026   1:34 PM      307500980 Chung 1 333333.MP3
-a----         4/10/2026   1:14 PM      288000676 Chung 1 nước mới.MP3
-a----         3/29/2026   1:38 PM      326624494 Chung 3 nước mới.MP3
-a----          4/9/2026   9:04 PM      276327076 Chung 5 .MP3
-a----          4/9/2026   2:23 AM      299994015 Chung4 nước mới).MP3
-a----         3/29/2026   1:53 PM      326624494 Nước Mới(chim nhẹ) để ghép.MP3
-a----         3/16/2026  11:02 PM      306169362 Âm 1 nước + Chim Top.MP3
-a----         3/22/2026  11:24 AM      248358058 âm 2 Nước.MP3


    Directory: D:\nhacdeghep\amluong\namkhanh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         10/6/2026   2:18 PM                game

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
