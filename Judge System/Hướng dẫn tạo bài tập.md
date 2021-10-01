# Hướng dẫn thêm bài vào hệ thống



## Xin quyền

- Liên hệ admin để xin quyền thêm bài.

  

## Hướng dẫn.

- Truy cập http://olp.hou.edu.vn/, đăng nhập.
- Tại góc trên bên phải, di chuột vào tài khoản, chọn **Quản trị**.

![image](https://drive.google.com/uc?export=view&id=1uqRCVa9KF4sfzYZxpR1XSWJ8I70n3CrO)

- Tại thanh điều hướng bên trái chọn đề bài, tại màn hình chính chọn, thêm vào.

![image](https://drive.google.com/uc?export=view&id=1r8U0ucbXAwpIpb1y_7wojclmqLmP8v3K)



- Tại các trường thông tin của bài đều có chú thích, mình sẽ liệt kê các trường cần điên và ghi chú cho những trường cần chú ý.

  - Mã đầu bài
  - Tên bài toán
  - Công khai
    - Thường các bài tập chia làm 2 mục đích, luyện tập và contest sắp tới, nếu là cho contest sắp tới thì ae không cần tích trường này.
  - Ngày xuất bản
  - Người tạo
  - Giám khảo
  - Người kiểm tra
  - Bài toán
    - Mình sẽ hướng dẫn cách viết đề bài sao cho đẹp ở mục dưới
  - Kiểu vấn đề(Problems Types)
    - Là mục nhỏ hơn của Nhóm đề bài (Problems Groups).
    - Vd : Chặt nhị phân với số thực, Chặt nhị phân với tổng tiền tố, ICPC Graphs Problems.
  - Nhóm của đề bài (Problems Groups)
    - Khi tìm kiếm sẽ có select box lọc theo trường này.
    - Vd : Luyện tập ICPC, Luyện Tập OLP, Graphs, DP , Chặt nhị phân.
  - Điểm
  - Giới hạn thời gian 
  - Giới hạn bộ nhớ :
    - Thường nếu vấn đề của ae không liên quan đến bộ nhớ, hay không yêu cầu vệ bộ nhớ thì có thể để là 524288 (tương đương với 512 mb).
  - Ngôn ngữ cho phép:
    - Tích hết các ô C/C++
    - Sau các bạn có phát triển được thêm thì có thể sửa text này.
  
  

## Hướng dẫn viết đề bài.

Hệ thống sử dụng Markdown hỗ trợ cho việc viết đề bài, về cú pháp các bạn có thể tham khảo link sau.

- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet



#### Biểu thức toán học

Để biểu diễn các biểu thức toán học các bạn có thể tham khảo link sau, các cú pháp tham khảo trong link dưới các bạn cần phải để vào giữa hai đấu "~" để có thể render ra đúng vd mình tìm trong link kia được mẫu cho biểu thức tổng như sau.
![image](https://drive.google.com/uc?export=view&id=1zmtAO2EU10zXeoEy6fw-JQ12o_133UUY)
Mình có thể viết là.

``` markdown
~ \sum_{k=1}^N k^2 ~
```



> https://en.wikipedia.org/wiki/Help:Displaying_a_formula



#### Hình ảnh minh họa

- Để quản lí gọn hình ảnh, tất cả các ảnh trong bài viết sé được lưu chung trong cùng 1 google drive được quản lí, hãy liên hệ với người quản lí clb để xin thư mục.

- Thêm ảnh vào thư mục nhận được, chuột phải chọn chia sẻ chọn Share.

- Ở phần Nhận đường liên kết, thay đổi đối tượng thành **Bất kì ai có đường liên kết**, và quyền là **Người xem**.

- Sao chép đường liên kết tới ảnh, liên kết sẽ có dạng sau https://drive.google.com/file/d/**<FILE_ID> ** /view , ta đổi thành https://drive.google.com/uc?export=view&id=/**<FILE_ID>** và dùng link này làm link của ảnh.

- Trong document ta thêm text sau :  
``` markdown
	![image](https://drive.google.com/uc?export=view&id=<FILE_ID>)
```



> https://stackoverflow.com/questions/52063556/add-image-to-github-readme-md-from-google-drive