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

Cài đặt PHP 5.6

    Tiến hành tải bản cài đặt PHP 5.6 về, có thể tải các phiên bản PHP dành cho Windows tại đây. https://windows.php.net/download/
    Tại hướng dẫn này, ta sử dụng phiên bản PHP 5.6 VC11 x64 Non Thread Safe (2018-Mar-01 06:22:32)
    Theo như yêu cầu của PHP ta cũng sẽ phải cài đặt thêm Visual C++ 11 x64 tại đây.
    Tải về và giải nén trên hệ thống, Ví dụ: C:\PHP\php56
  Truy cập vào PHP Manager và chọn Register New PHP version
  Chọn tới file php-cgi.exe trong thư mục php56 vừa giải nén
  Restart lại IIS
 #Cài đặt My SQL

      Trước khi cài đặt My SQL, cần cài đặt dotnetfx 4.5.2
      Cài đặt thêm VC++ 2010, VC++ 2013
      Để cài đặt My SQL, có thể download tại đây. https://dev.mysql.com/downloads/windows/installer/5.6.html
      Tại đây ta download phiên bản 5.6.39
      IMS-42.png
      ![alt text](https://github.com/dzung042/iis-php-mysql/blob/master/image/IMS-42.png)
