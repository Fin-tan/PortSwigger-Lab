# WEB
*SQL injection vulnerability allowing login bypass*
## Tóm tắt
- Tận dụng lỗ hổng sql injection để truy cập web với quyền admin
## Khai thác 
1. truy vập vào phần Myaccount để login 

![alt text](images/image.png)

2. Điền username với admin' or '1'='1' -- và password là bất kì thì truy cập vào được với quyền admin

![alt text](images/image-1.png)

![alt text](images/image-2.png)
