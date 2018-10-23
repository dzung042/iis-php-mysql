# iis-php-mysql
#1: Cài IIS active CGI
#Bước 2: Cài đặt PHP 5.6
1: Cài IIS active CGI

Bước 2: Cài đặt PHP 5.6

Cài đặt PHP Manager

PHP Manager được sử dụng để quản lý các phiên bản PHP trên hệ thống, cũng như đơn giản hoá việc sử dụng PHP. Khi sử dụng PHP manager, chỉ cần vài thao tác chuột là đã có thể add thêm 1 phiên bản PHP sử dụng cũng như tuỳ biến các extension PHP.

Để cài đặt PHP Manager, trước hết cần cài đặt Dotnet 3.5

Tại Server Manager > Features > Add Features

Chọn Dotnet FrameworkFramework 3.5.1 Features > Next

Tải PHP Manager tại đường dẫn sau

Tiến hành chọn phiên bản phù hợp, tại đây ta chọn phiên bản cho IIS 7 64bit, ứng với hệ thống đang sử dụng

Tiến hành cài đặt PHP Manager theo các bước hướng dẫn của phần mềm.

Sau khi cài đặt xong PHP Manager, tiến hành khởi động lại hệ thống VPS/Server

Sau khi hệ thống đã khởi động lại, truy cập vào IIS và kiểm tra trạng thái của PHP Manager

![alt text](https://github.com/dzung042/iis-php-mysql/blob/master/image/IMS-11-600x344.png)

Sau khi hệ thống đã khởi động lại, truy cập vào IIS và kiểm tra trạng thái của PHP Manager
