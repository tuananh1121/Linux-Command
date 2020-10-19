# Linux Command
## Mục lục
|1-10|11-20|21-30|31-40|41-50|
|-|-|-|-|-|
|[1. pwd](#pwd)|-|-|-|-|
|[2. cd](#cd)|-|-|-|-|
|[3. ls](#ls)|-|-|-|-|
|[4. mkdir](#mkdir)|-|-|-|-|
|[5. touch](#touch)|-|-|-|-|
|[6. rm](#rm)|-|-|-|-|
|[7. cp](#cp)|-|-|-|-|
|[8. mv](#mv)|-|-|-|-|
## 1. pwd command <a name="pwd"></a>
Dùng để hiển thị đường dẫn thư mục hiện tại

![](/image/pwd.png)

## 2.cd command <a name="cd"></a>
Dùng để di chuyển qua lại giữa các thư mục

### 2.1 cd /
Dùng để di chuyển về thư mục `root` dù đang ở thư mục nào

![](/image/cd1.png)

### 2.2 cd ~
Dùng để di chuyển về thư mục home 

![](/image/cd2.png)

### 2.3 cd ..
Dùng để di chuyển về thư mục cha của thư mục hiện tại

![](/image/cd3.png)

### 2.4 cd -
Dùng để di chuyển về thư mục trước đó đã thoát

![](/image/cd4.png)

## 3. ls command <a name="ls"></a>
Liệt kê các tệp và thư mục:quyền,user,kích thước,.....

### 3.1 ls -a
Hiển thị các file ẩn

![](/image/ls1.png)

### 3.2 ls -l 
Hiển thị đầy đủ các file, thư mục,quyền, kích thước,....

![](/image/ls2.png)

### 3.3 ls -h
Hiển thị các file, thư mục mà người dùng dễ đọc

![](/image/ls3.png)

### 3.4 ls -x
Hiển thị file, thư mục theo bảng chữ cái

![](/image/ls4.png)

### 3.5 ls -t 
Hiển thị thứ tự sắp xếp theo thời gian sửa đổi

![](/image/ls5.png)

### 3.6 ls -R
Hiển thị file theo dạng cây thư mục và đường dẫn

![](/image/ls6.png)

### 3.7 ls -1
Hiển thị mỗi thư mục trên 1 dòng

![](/image/ls7.png)

### 3.8 ls -ld /etc
Hiển thị thông tin thư mục

![](/image/ls8.png)


## 4. mkdir <a name="mkdir"></a>
Tạo thư mục ở vị trí hiện tại đang đứng

Tạo nhiều thư mục

![](/image/mkdir1.png)

### 4.1 mkdir -p 
Tạo thư mục con khi chưa có thư mục cha

![](/image/mkdir2.png)

### 4.2 mkdir -m
Tạo thư mục và phân quyền cho thư mục

![](/image/mkdir3.png)

## 5. touch <a name="touch"></a>
Dùng để tạo file trống
```
# touch <file name>
```

Tạo nhiều file trống

```
# touch <file1> <file2> <file3>
```
## 6. rm <a name="rm"></a>
Dùng để xóa file hoặc thư mục

### 6.1 rm <tên file>
```
rm <tên file>
```

Xóa nhiều file

``` 
rm <file1> <file2> <file3>
```

### 6.2 rm <option> <tên file>

* Option:
 * `-r`: hỏi trước khi xóa
 * `-f`: xóa không cần hỏi
 * `-I`: xóa các thưc mục có tên gần giống nhau
 * `-v`: hiển thị kết quả xóa

## 7. cp <a name="cp"></a>
Dùng để xóa chép file hoặc thư mục

* Sao chép nội dung 1 file vào 1 file khác. Nếu file đích đó chưa tồn tại thì sẽ tạo ra file đó với nội dung giống hệt file nguồn.

```
# cp <file nguồn> <file đích>
```
* Copy file vào thư mục khác 

![](/image/cp1.png)

* `# cp <options> `
 * Options:
  * `-n`: ép buộc lệnh copy không được ghi đè nếu file nguồn và file đích cùng tên
  * `-f`: ép buộc lệnh copy ghi đè nếu file nguồn và file đích cùng tên
  * `v`: hiển thị quá trình copy

### 7.1 cp -r/-R
Copy toàn bộ thư mục

![](/image/cp2.png)

## 8. mv <a name="mv"></a>
Dùng để di chuyển file hay thư mục.Trong một số trường hợp cũng dùng để đổi tên file hoặc thư mục

* Đổi tên file hay thư mục
```
# mv file1 file2
```

Di chuyển file hoặc thư mục đến thư mục khác

```
# mv file1 /home/tuananh
```
### 8.1 mv -f
Ghi đè lên tệp đích và xóa tệp nguồn

![](/image/mv1.png)

### 8.2 mv -v
Hiển thị quá trình di chuyển hoặc đổi tên

![](/image/mv2.png)

## 9. head <a name="head"></a>
Dùng để in phần đầu của tệp tin

```
# head <tên file>
```
mặc định in ra 10 dòng đầu tiền 

![](/image/head1.png)

Cũng có thể cùng một lúc dùng cho nhiều file

![](/image/head2.png)

### 9.1 head -n
Dùng để hiển thị số dòng muốn xem. Ví dụ muốn hiển thị ra 3 dòng đầu tiên

![](/image/head3.png)

### 9.2 head -v
Hiển thị cùng với tên file

![](/image/head4.png)

## 10. tail <a name="tail"></a>
Hiển thị những dòng cuối cùng của file. Cũng giống như lệnh `head`, `tail` cũng hiển thị ra 10 dòng

![](/image/tail1.png)

Tương tự với nhiều file

![](/image/tail2.png)

### 10.1 tail -n
Hiển thị ra số dòng muốn lấy

![](/image/tail3.png)

### 10.2 tail -v
Hiển thị cùng với tên file

![](/image/tail4.png)

### 10.3 tail -f
Dùng để theo dõi file log

Khi sử dụng câu lệnh `tail -f` nó sẽ in ra và cập nhật **liên tục** những dòng cuối cùng của file

![](/image/tail5.png)

## 11 cat <a name="cat"></a>

Dùng để tạo, xem nội dung file

* Xem nội dung file

![](/image/cat1.png)

* Tạo file

![](/image/cat2.png)

Khi tạo và điền thông tin vào file xong ta gõ `ctrl+d` để thoát và lưu file

* Copy nội dung file

![](/image/cat3.png)

Lưu ý: Nội dung file nguồn sẽ ghi đè lên nội dung file đích

* Thêm nội dung file

![](/image/cat4.png)

Lưu ý: Nội dung file nguồn sẽ thêm vào cuối nội dung của file đích