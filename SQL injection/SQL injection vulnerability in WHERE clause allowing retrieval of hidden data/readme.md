# WEB
*Lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data*
## Tóm tắt
- challenge cho phép sửa URL để truy vấn SQL,tận dụng lỗ hổng SQL injection để khai thác 
## Khai thác
1. **Tìm lỗ hổng của web**
![alt text](images/image.png)

- Trong Refine your search ta thử nhấn vào 1 trong những button trong đó 

![alt text](images/image-1.png)
2. **Khai thác trang web**
- Thêm vào URL 'or 1=1-- ta đã truy vấn được tất cả các sản phẩm khác 

![alt text](images/image-2.png)

