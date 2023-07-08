# Hide and seek
![img]()

* Đề bài cho ta một trang web cho phép comment và ở ô điền tên có lỗ hổng XSS nên mình đã mày mò mãi ở chỗ đó mà quên mất mô tả của bài ```source code is everything```. Kiểm tra source:

![img]()

* Ở phần ```/static/bootstrap.min.css```, ```/static/bootstrap.css``` và ```https://www.w3schools.com/w3css/4/w3.css``` đều không có gì đặc biệt cả, kiểm tra ```/static/bootstrap.min.js``` ta thấy đoạn code sau:

![img]()

* Try cập vào ```/secret-terces007``` và bị rick roll

![img]()

* Tiếp tục đọc source và tìm thấy flag ```Flag{d3v3lop3r_t00l_1s_c00l}```