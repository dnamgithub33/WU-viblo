# Are you a robot?

![img](https://github.com/dnamgithub33/Wu-viblo/blob/1b3558bfe32028df76e0f360b6a7188e7c61c6d7/Are%20you%20a%20robot/1.png)

* Đề bài cho ta một trang web cho phép nhập captcha. Nếu đúng thì báo ta không phải robot, sai thì bảo ta là imposter.

* Kiểm tra file ```robots.txt``` ta nhận được danh sách ```User-agent``` và ```Disallow```.

![img](https://github.com/dnamgithub33/Wu-viblo/blob/1b3558bfe32028df76e0f360b6a7188e7c61c6d7/Are%20you%20a%20robot/2.png)

* Để ý đến User-agent ```baiduspider``` có liên quan đến hint của đề, sử dụng burp repeater thay đổi User-agent và url trỏ đến Disallow tương ứng, send và lấy được flag.

![img](https://github.com/dnamgithub33/Wu-viblo/blob/1b3558bfe32028df76e0f360b6a7188e7c61c6d7/Are%20you%20a%20robot/3.png)