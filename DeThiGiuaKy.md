# Hướng dẫn thực hiện đề thi giữa kỳ
## Đề 1
### Câu 1: Sử dụng các lệnh cơ bản trong Linux để thực hiện các thao tác sau:
***Lưu ý : chỉ sử dụng các lệnh cơ bản của Linux*** 
1. Xem đường dẫn thư mục hiện hành
```console
pwd
```
Ví dụ in ra: ```/home/ncduc```

2. Tạo một thư mục mới mang tên MSSV của bạn (Vd: 1752001)
```console
mkdir 1752001
```

3. Chuyển thư mục hiện hành vào thư mục bạn vừa tạo ở câu 2
```console
cd 1752001
```
4. Tạo một thư mục mang tên MidTerm
```console
mkdir MidTerm
```

5. Tạo một file mới mang tên newfile.txt
```console
touch newfile.txt
```
6. Copy file newfile.txt vào thư mục MidTerm
```console
cp newfile.txt MidTerm/
```

7. Đổi tên file newfile.txt trong thư mục MidTerm thành ketqua.txt
```console
mv MidTerm/newfile.txt MidTerm/ketqua.txt
```

8. Thêm vào file ketqua.txt dòng sau
```txt
# Day la file ket qua cua sinh vien MSSV_cua_ban
```
```console
echo "# Day la file ket qua cua sinh vien 1752001" >> MidTerm/ketqua.txt
```

9. Hiển thị nội dung của file MidTerm/ketqua.txt
```console
cat MidTerm/ketqua.txt
```

10.	Hiển thị thông tin đầy đủ của file MidTerm/ketqua.txt
```console
ls -l MidTerm/ketqua.txt
```

### Câu 2
1.	Hãy tìm tất cả những file bắt đầu bằng ký tự b.
```console
ls b*
```
2.	Tìm tất cả các file kết thúc bằng ký t.
```console
ls *t
```
3.	Tìm tất cả các file bắt đầu bằng r hoặc w.
```console
ls {r,w}*
```
4.	Tìm tất cả các file có chứa ll.
```console
ls *ll*
```
5.	Tìm tất cả các file bắt đầu bằng white hoặc black.
```console
ls {black,white}*
```
6.	Tìm tất cả các file bắt đầu bằng red hoặc yellow và kết thúc bằng short.
```console
ls {red,yellow}*{short}
```
7.	Tìm tất cả các file có chứa tshirt và short.
```console
ls *{tshirt,short}*{short,tshirt}*
```
hoặc
```console
ls *tshirt*short*
```
8.	Tìm tất cả các file trong đó màu thứ nhất là red hoặc blue hoặc green và màu thứ hai là white hoặc black.
```console
ls *{red,blue,green}*{white,black}*
```
9.	Tìm tất cả các file không bắt đầu bằng r.
```console
ls [!r]*
```
10.	Tìm tất cả các file không kết thúc bằng s.
```console
ls *[!s]
```
### Câu 3

## Đề 2
### Câu 1
### Câu 2
### Câu 3