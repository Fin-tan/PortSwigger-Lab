# Path traversal
*Lab: File path traversal, traversal sequences blocked with absolute path bypass*
## Tóm tắt 
- Tận dụng lỗ hổng đường dẫn tệp của web để truy cập các file hệ thống quan trọng 
## Khai thác
1. Dùng Burpsuite để lấy URL api load ảnh của web 

![alt text](images/image.png)

2. Tiến hành tăng cấp thư mục để tìm file etc/passwd
- sử dụng đường dẫn trực tiếp /etc/passwd

![alt text](images/image-1.png)

![alt text](images/image-2.png)