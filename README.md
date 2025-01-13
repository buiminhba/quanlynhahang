## Các chức năng chính trong ứng dụng
----------------
### Chức năng chính cho khách hàng
> * Đăng nhập
> * Đăng ký tài khoản
> * Đặt bàn và gọi món
> * Đổi điểm tích lũy
> * Quản lý thông tin cá nhân 
> * Xem lịch sử hóa đơn

### Chức năng nhân viên (bao gồm cả nhân viên tiếp tân, nhân viên kho và quản trị viên)
>*  Đăng nhập
>*	Quản lý Bàn
>*	Quản lý Nguyên Liệu
>*	Quản lý Kho
>*	Quản lý Nhập Kho
>*	Quản lý Xuất Kho
>*	Quản lý Thực Đơn
>*	Quản lý Nhân Sự
>*	Báo cáo Doanh Thu
>*	Thống kê Hóa Đơn
>*	Quản lý khách hàng

## Demo Sản Phẩm
-  Đăng Ký & Đăng Nhập:
----------------
>* Đăng Ký

![SignUp](./src/Demo/SignUp.png)

>* Đăng Nhập

![SignIn](./src/Demo/SignIn.png)

-  Khách Hàng:
----------------
>* Đặt Món

![OrderFood](./src/Demo/Customer/OrderFood.png)

>* About Us

![AboutUs](./src/Demo/Customer/AboutUs.png)

>* Thông Tin Cá Nhân

![Profile](./src/Demo/Customer/Profile.png)

-  Admin:
----------------
>* Quản Lý Thực Đơn

![MenuManage](./src/Demo/Admin/Manage_Food.png)  

>* Sửa Thực Đơn

![EditFood](./src/Demo/Admin/Edit_Food.png)

>* Báo cáo & Thống Kê

![Statistic](./src/Demo/Admin/Statistic.png)

## Các ngôn ngữ, công nghệ sử dụng
> * Ngôn ngữ sử dụng: `Java`
> * IDE sử dụng: `Netbeans`
> * Công cụ lập trình giao diện: `JavaSwing`
> * Cơ sở dữ liệu: `Oracle`
> * Công cụ quản lý phiên bản: `Git`
>* Công cụ quản lý mã nguồn `Github`
>* ­Công cụ vẽ sơ đồ phân tích và thiết kế dữ liệu: `StarUML`, `draw.io`.

## Yêu cầu cài đặt
> * Sử dụng `JDK 17`
> * Sử dụng `ojdbc8.jar`

## Hướng dẫn cài đặt chương trình
> * **Bước 1:** Clone project [Java_Project_RestaurantMS](https://github.com/VietNguyen2003-UIT/Java_Project_RestaurantMS)
> * **Bước 2:** Vào Netbeans chọn Open project và mở project vừa clone về.
> * **Bước 3:** Thêm tất cả các thư viện cần thiết trong mục src/External_Library.
> * **Bước 4:** Trong src/DataBase có file Database.sql. Tiến hành vào Oracle tạo user mới với Username là `Doan` và Password là `123`, sau đó chạy toàn bộ file Database.sql.
> * **Bước 5:** Tiến hành chạy run file src/RTDRestaurant/View/Main_Frame/Main_LoginAndRegister.java để chạy chương trình
>* ***Note:** Xem file hướng dẫn cài đặt dưới đây để hiểu rõ thêm: [File hướng dẫn chi tiết](https://docs.google.com/document/d/10h0v1Bf-x-AGbSoLZw1hegSK2QQK_oClz71aKmKWJ04/edit?usp=sharing)*

## Tài liệu tham khảo

 - [Java Swing UI Design - Register and Verify Code With Email](https://github.com/DJ-Raven/java-swing-login-ui-001)
 - [Java Swing UI Design - School Management Dashboard](https://github.com/DJ-Raven/java-swing-school-management-dashboard)
 - [Java UI Design - Dashboard Desktop Application](https://github.com/DJ-Raven/java-ui-dashboard-008)
