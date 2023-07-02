# Are you a robot?

![img]()

* Đề bài cho ta một trang web cho phép nhập captcha. Nếu đúng thì báo ta không phải robot, sai thì bảo ta là imposter.

* Kiểm tra file ```robots.txt``` ta nhận được danh sách ```User-agent``` và ```Disallow```.

![img]()

* Để ý đến User-agent ```baiduspider``` có liên quan đến hint của đề, sử dụng burp repeater thay đổi User-agent và url trỏ đến Disallow tương ứng, send và lấy được flag.

![img]()