# elolms-2021-khongchinhsuaanhien-cn09
Chức năng: Ở diễn đàn thảo luận, hiện tại giảng viên có thể sửa bài viết của SV => request: không cho sửa bài của SV, đồng thời thêm nút ẩn bài nếu bài post vi phạm quy định  
Yêu cầu: thực hiện sau chức năng elolms-2021-khongchophepsvdangbaimoi-cn08 `https://github.com/OU-University/elolms-2021-khongchophepsvdangbaimoi-cn08`  
Hướng dẫn:  
+ Cập nhật đường dẫn:
  - mod/forum/lang/vi/forum.php
  - mod/forum/lang/en/forum.php
  - mod/forum/db/access.php
  - mod/forum/post.php
  - mod/forum/lib.php
  - mod/forum/version.php
  - mod/forum/styles.css
 + cập nhật quyền Giảng viên, trợ giảng 
    - Hide any posts (anytime) : Allow
    - Hide own posts (within deadline): Allow
 + cập nhật quyền Sinh viên
    - Hide any posts (anytime) : Not set
    - Hide own posts (within deadline): Not set  
============================================================      
 + Không cho giáo viên , sinh viên xóa và chỉnh sửa bài post giảng viên, sinh viên  
    - Delete any posts (anytime) : Not set  
    - Delete own post (within deadline): Not set  

========================================
Đầu ra mong muốn   
Ẩn 
![1-Hide](https://user-images.githubusercontent.com/84503105/121505466-0f98f480-ca0d-11eb-910d-1c72bd4b9dea.png)

Xác nhận ẩn bài đăng
![2-ConfirmHiding](https://user-images.githubusercontent.com/84503105/121505475-10ca2180-ca0d-11eb-990b-89bea2640ee2.png)

Hiện
![3-Show](https://user-images.githubusercontent.com/84503105/121505488-132c7b80-ca0d-11eb-9541-f4ab159cd515.png)

 Xác nhận hiện bài đăng
![4-ConfirmShowing](https://user-images.githubusercontent.com/84503105/121505491-145da880-ca0d-11eb-9a45-f2f27348f265.png)
