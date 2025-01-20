
## 💝 Ủng hộ tôi

### Nếu bạn thấy dự án của tôi hữu ích và muốn ủng hộ tôi, hãy quét mã QR bên dưới:

| ![QR Code for MoMo](./img_github_momo_donate.png)                                                                             | ![Thank you](./img_thank_you.gif) | ![QR Code for Bank](./img_github_tech_donate.png) | ![Thank you](./img_thank_you.gif) |
|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------|---------------------------------------------------|-----------------------------------|
| **Momo:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br/>0981054498 - NGUYEN ANH DAT** | **Thank you 🙌**                  | **Techcombank:<br/>1981054498 - NGUYEN ANH DAT**  | **Thank you 🙌**                  |

### Cảm ơn sự hào phóng của bạn! 🙌

---

# Giới thiệu dự án Medical

### Mô tả

- Dự án **Medical** là một dự án quản lý khám bệnh, có giao diện đơn giản. Tôi code cơ bản và dễ hiểu, phù hợp với ai mới học. Bạn có thể dùng **Medical** như một tài liệu tham khảo hoặc dùng làm bài tập của mình.
- Dự án **Medical** có 2 thư mục là 2 ứng dụng khác nhau:
    - Thư mục **medical-be** là ứng dụng API
    - Thư mục **medical-fe** là ứng dụng web trang quản lý
- Back-End Framework: **ExpressJS**
- Front-End Framework: **ReactJS**

### Cài Đặt
<details>
<summary>Click để mở rộng</summary>
<br>

1. **Yêu cầu Node.js**
- Đảm bảo bạn đã cài đặt Node.js trên máy tính.

2. **Clone repository**
- Clone repository từ Github vào máy tính của bạn.

3. **Cài đặt medical-be**
- Bạn cần cài đặt ứng dụng API trước tiên.
- Mở thư mục **medical-be** bằng `VSCode` hoặc IDE của bạn, sau đó mở Terminal và chạy lệnh sau để cài đặt các dependencies:
    ```sh
    npm install
    ```
    hoặc
    ```sh
    yarn install
    ```
4. **Cấu hình biến môi trường**
- Mở tệp `.env.example`, đổi tên tệp thành `.env`, và điền các thông tin sau:
    - **PORT**: cổng mà API chạy
    - **PORT_SOCKET**: cổng mà Socket chạy
    - **MONGO_URL**: địa chỉ kết nối tới CSDL

5. **Ví dụ biến môi trường**
- Tệp `.env` có thể có nội dung như sau:
    - **PORT**: `8081`
        - `8081` là do bạn đặt, sao cho không trùng với cổng của các ứng dụng khác.
    - **PORT_SOCKET**: `3000`
        - `3000` là do bạn đặt, sao cho không trùng với cổng của các ứng dụng khác.
    - **MONGO_URL**: `mongodb://root:pass@localhost:27017`
        - Tôi đang sử dụng **Docker** để cài đặt **MongoDB**. Bạn cài đặt **Docker Desktop** vào máy. Sau đó, di chuyển đến thư mục **Medical**, nơi chứa file `docker-compose.yml`. Mở Terminal và chạy lệnh sau để cài đặt:
            ```sh
            docker-compose up -d
            ```
        - Bạn có thể cài đặt **MongoDB** trên máy và tạo 1 database cụ thể ví dụ database Medical chẳng hạn. Khi đó **MONGO_URL** sẽ thay đổi.

6. **Cài đặt medical-fe**
- Mở thư mục **medical-fe** bằng `VSCode` hoặc IDE của bạn, sau đó mở Terminal và chạy lệnh sau để cài đặt các dependencies:
    ```sh
    npm install
    ```
    hoặc
    ```sh
    yarn install
    ```

</details>


### Chạy thử
<details>
<summary>Click để mở rộng</summary>
<br>

1. **Chạy medical-be**

- Tạo tài khoản Admin:
    ```sh
    npm run createAdmin
    ```
    hoặc
    ```sh
    yarn createAdmin
    ```
    - Tài khoản Admin:
        ```js
        {
            password: "123456",
            activeStatus: true,
            userType: "admin",
            name: "Admin",
            email: "admin@gmail.com",
            fullName: "Admin",
            gender: "male"
        }
        ```

- Tài khoản Admin có thể thêm tài khoản người dùng với các chức vụ khác nhau. Mật khẩu mặc định của các tài khoản này là `123456`

- Khởi chạy dev:
     ```sh
    npm run dev
    ```
    hoặc
    ```sh
    yarn dev
    ```
- Khởi chạy product:
     ```sh
    npm run start
    ```
    hoặc
    ```sh
    yarn start
    ```

2. **Chạy medical-fe**
- Khởi chạy dev:
     ```sh
    npm run dev
    ```
    hoặc
    ```sh
    yarn dev
    ```

</details>

#### Màn hình

<details>
<summary>Click để mở rộng</summary>

| ![](./Screenshot_1733978627.png) | ![](./Screenshot_1733978628.png)  |
|----------------------------------|-----------------------------------|
| ![](./Screenshot_1733978629.png) | ![](./Screenshot_1733978630.png)  |
| ![](./Screenshot_1733978631.png) | ![](./Screenshot_1733978632.png)  |
| ![](./Screenshot_1733978633.png) | ![](./Screenshot_1733978634.png)  |

</details>

https://github.com/user-attachments/assets/fd4415f8-e723-4620-b8d6-bdf19bd85190
