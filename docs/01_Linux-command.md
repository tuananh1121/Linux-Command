# Linux Command
## Mục lục
|1-10|11-20|21-30|31-40|41-50|
|-|-|-|-|-|
|[1. pwd](#pwd)|-|-|-|-|
|[2. cd](#cd)|-|-|-|-|
|[3. ls](#ls)|-|-|-|-|
|[4. mkdir](#mkdir)|-|-|-|-|
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