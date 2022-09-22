---
title: "Các cách triển khai Authentication"
date: 2022-09-22T22:51:41+07:00
draft: false
---
Bài viết này sẽ giới thiệu cơ bản về authentication là gì, và các phương pháp triển khai trong hệ thống thực tế
### Authentication là gì?
Authentication là quá xác thực thông tin người dùng xem có tồn tại trong hệ thống hay không thông qua thông tin đăng nhập, nếu có, ngưởi dùng sẽ được cấp phép truy cập vào hệ thống.
* Authentication không chỉ dùng để xác thực người dùng.
* Username và password không phải là cách duy nhất để xác thực người dùng.
### Authentication hoạt động như thế nào?
Một số phương thức authentication cơ bản như sau:
* Username password.
* Mã Pin, câu hỏi bảo mật.
* Token: sử dụng thiết bị ngoại vi như USB, ổ cứng đóng vài trò như chìa khóa (Hard token). Sử dụng mật khẩu dùng một lần OTP (Soft token)
* Sinh trắc học: vân tay, mống mắt, nhận diện khuôn mặt, giọng nói.
### Một vài cách triển khai Authentication cho hệ thống.
* Basic Authentication
Sử dụng bộ giao diện authentication được cung cấp sẵn bởi trình duyệt.
* Session based Authentication
* Token based Authentication
* JWT Authentication
* OAuth - Open Authentication
* Single Sign On - SSO
***
Ở bài viết sau mình sẽ lần lượt đi vài triển khai chi tiết các phương pháp Authentication, cùng đón xem nhé ^^ 